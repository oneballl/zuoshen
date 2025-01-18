
# 1 拷贝和引用
```py
p = [4,6,7]
ret = []
k = []
k.append(p[:])#拷贝，改变原列表不会改变拷贝后的值
#或者
k.append(p.copy[])

ret.append(p)
print(ret)
print(k)
p.pop()
print(ret)
print(k)
```
# 2进制转换
```py
#16 转 2(先转10再转2)
#(bin带有两位数的前缀，所以加上[2：]舍弃前缀)
a = "FF"
b = bin(int(a,16))[2:]
# 10 转2
c = 8
d = bin(c)[2:]

#2 转 8
oct(int(a,2))[2:]
#2转16
hex(int(a,2))[2:]


```
# 3二分查找bisect模块
找插入的位置

```py
>>> import bisect
>>> a = [1,3,5,7,9]
>>> print(bisect.bisect(a,6))
3
```
# 4 判断字符串收据类型

```py
str.isalpha()字母
islower()小写
isupper()大写
istitle()单词首字母大写
isdigit()数字
isalnum()数字或字母
```

# 5字典
Python 中的 get() 方法用于从字典中获取指定键的值。如果键不存在，则返回一个默认值
Python 字典keys() 函数以列表返回一个字典所有的键
Python 字典 popitem() 方法随机返回并删除字典中的最后一对键和值 popitem(last = False)可以弹出最早的值



> 
> Written with [StackEdit中文版](https://stackedit.cn/).

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAxNzEzOTE5XX0=
-->