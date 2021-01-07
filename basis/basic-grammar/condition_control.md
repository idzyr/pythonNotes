# 条件控制

## if

**语法；**

```python
if 布尔表达式:
    布尔表达式为True时执行的代码
```



**示例；**

```python
if 1 > 0:
    print("大于0")
    
# 输出结果   大于0      
```



## if...else

**语法；**

```python
if 布尔表达式:
   布尔表达式为True时执行的代码
else: 
   布尔表达式为False时执行的代码
```



**示例；**

```python
if 0 > 0:
    print("大于0")
else: 
    print("不大于0")
    
# 结果； 不大于0   
```



## if...elif...else


**语法；**

````python
if 布尔表达式1:
   布尔表达式1为True执行的代码。
elif 布尔表达式2:
   布尔表达式2为True执行的代码。
elif 布尔表达式3:
   布尔表达式3为True执行的代码。
else:
   以上所有布尔表达式没有一个为True时执行的代码。
````

> **注意；**
>
> ​	以上1~3个布尔表达式无论那个为True那么剩余的其它表达式将不会在被执行。



**示例；**

```python
number = 4
if number == 1:
    print("error")
elif number > 4:
    print("yew")
elif number < 3:
    print("错误")
else:
    print("正确答案是4")
    
# 最终执行结果为  正确答案是4
```

