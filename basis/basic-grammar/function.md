# 函数

> **注意；**
>
> 必须先定义函数才可以调用，定义函数前面要用两行空行，方便阅读代码。



## 函数声明

- 无返回值无参数

**语法；**

```python
 def 方法名():
    方法体……
```

**示例；**

```python
def fn():
    print("My function")
```




- 带参数
  

**语法；**

```python
  def 方法名(形参1，形参2，等):
      方法体……
```

**示例；**

```python
def fn1(name):
    print(name,"执行了我")
```

- 带返回值
> **提示；**‘
> 	如果返回的内容是元组，那么可以省略()

**语法；**

  ```python
def 方法名(形参1，形参2，等):
    方法体……
    return 返回值
  ```



**示例；**

```python
def fn2():
  	print("带返回值方法")
	return "返回我被执行了"
```



## 函数调用

```python

print("-"*10)

# 定义一个测试方法
def functionDemo():
    print("方法体被调用")


functionDemo()
#调用方法
    

```

执行结果；

```
----------
方法体被调用
```







## 函数功能注释

```python
def fn():
    """  添加多行注释
    打印内容
    :return: 无返回值
    """
    print("My function")

```

