# Signal
实现思路：
将要计算的初始值写入一个txt文档中，读取这个txt文件，将其多行多列转换为一个ListMap，然后再控制台输入要查看状态的行，然后通过行号去ListMap中寻找对应的值进行计算得到结果显示在控制台。  

结果展示：   

```
输入文件的内容是：
====================================
	Plane1 1 1 1
	Plane1 1 1 1 1 2 3
	Plane1 2 3 4 1 1 1
	Plane1 3 4 5 
	Plane1 1 1 1 1 2 3
====================================
请输入正确的要查询的无人机消息序号：
输入 "end" 结束查询。
请输入：
-1
请输入大于零的数。
请输入：
0
Plane1 0 1 1 1
请输入：
1
Plane1 1 2 3 4
请输入：
2
Plane1 2 3 4 5
请输入：
3
Error：3
请输入：
4
Error：4
请输入：
5
Cannot find 5
请输入：
6
Cannot find 6
请输入：
end
应用运行结束。
```
