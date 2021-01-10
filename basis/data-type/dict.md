# dict【字典】

- 字典用 `{}` 定义
- 字典使用 **键值对** 存储数据，键值对之间使用 `,` 分隔
  - **键** `key` 是索引
  - **值** `value` 是数据
  - **键** 和 **值** 之间使用 `:` 分隔
  - **键必须是唯一的**
  - **值** 可以取任何数据类型，但 **键** 只能使用 **字符串**、**数字**或 **元组**

**语法；**

```
dict_deom = {
    键1:值1,
    键2:值2,
}
```



**示例；**

```python
miku_dict = {
    "name": "初音未来",
    "age": 18,
    "gender": False,
    "height": 160.0,
}


# 通过key获取value
print(miku_dict["name"])

# 遍历字典
for ks in miku_dict:
    print(miku_dict.get(ks)) #通过遍历的key获取value


# 获取字典长度
print("字典长度%d" % len(miku_dict))

# 通过key修改value
miku_dict["age"] = 16
print(miku_dict)
```



## 字典一些api

> **文档；**
>
> ​	https://docs.python.org/zh-cn/3.7/library/stdtypes.html#dict

```
dict.clear       dict.items       dict.setdefault
dict.copy        dict.keys        dict.update
dict.fromkeys    dict.pop         dict.values
dict.get         dict.popitem    
```





