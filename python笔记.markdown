#Python基础
##变量和简单数据类型
###python中的变量
- 变量名只能包含字母、数字和下划线。变量名可以字母或下划线打头，但不能以数字打头。
- 变量名不能包含空格，但可以使用下划线来分隔其中的单词。
- 不能将 **Python** 中的关键字和函数名用作变量名，即不要使用 **Python** 保留用于特殊用途的单词。
- 变量名应既简短又具有描述性。
- 慎用小写字母 **l** 和大写字母 **O** 
###字符串
####使用方法修改字符串的大小写
```
name = "ada lovelace"
print (name.title())
```
得到的结果为：
```
Ada Lovelace
```
***title()***以首字母大写的方式显示每个单词，类似的还有 ***upper()*** 和 ***lower()***
```
name = "ada lovelace"
print (name.upper())
print(name.lower())
```
这些代码输出如下：
```
ADA LOVELACE
ada lovelace
```
####合并（拼接）字符串
在python中使用' + '来合并字符串，使用多个' + '来合并多个字符串的方法可以称作拼接。
```
first_name = "ada"
last_name = "lovelace"
full_name = first_name + " " + last_name

print (full_name)
```