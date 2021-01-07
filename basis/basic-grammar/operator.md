# 运算符

## 算数运算符

| 运算符 | 描述   | 实例                                       |
| :----- | ------ | ------------------------------------------ |
| +      | 加     | 10 + 20 = 30                               |
| -      | 减     | 10 - 20 = -10                              |
| *      | 乘     | 10 * 20 = 200                              |
| /      | 除     | 10 / 20 = 0.5                              |
| //     | 取整除 | 返回除法的整数部分（商） 9 // 2 输出结果 4 |
| %      | 取余数 | 返回除法的余数 9 % 2 = 1                   |
| **     | 幂     | 又称次方、乘方，2 ** 3 = 8                 |

- \* 可以对字符串运算，就字符串复制拼接。

  ```python
  "a" * 5 # 会拼接5个a。
  # 输出结果；aaaaa
  ```

### 算数运算符的优先级

- 和数学中的运算符的优先级一致，在 Python 中进行数学计算时，同样也是：
  - **先乘除后加减**
  - 同级运算符是 **从左至右** 计算
  - 可以使用 `()` 调整计算的优先级
- 以下表格的算数优先级由高到最低顺序排列

| 运算符   | 描述                   |
| -------- | ---------------------- |
| **       | 幂 (最高优先级)        |
| * / % // | 乘、除、取余数、取整除 |
| + -      | 加法、减法             |

**例如：**

- `2 + 3 * 5 = 17`
- `(2 + 3) * 5 = 25`
- `2 * 3 + 5 = 11`
- `2 * (3 + 5) = 16`

## 逻辑运算符

| 运算符 | 说明       | 逻辑表达式 | 描述                                                         |
| ------ | ---------- | ---------- | ------------------------------------------------------------ |
| and    | 与         | x and y    | 只有 x 和 y 的值都为 True，才会返回 True 否则只要 x 或者 y 有一个值为 False，就返回 False |
| or     | 或         | x or y     | 只要 x 或者 y 有一个值为 True，就返回 True 只有 x 和 y 的值都为 False，才会返回 False |
| not    | 非（取反） | not x      | 如果 x 为 True，返回 False 如果 x 为 False，返回 True        |

## 赋值运算符

- 在 Python 中，使用 `=` 可以给变量赋值
- 在算术运算时，为了简化代码的编写，`Python` 还提供了一系列的 与 **算术运算符** 对应的 **赋值运算符**
- 注意：**赋值运算符中间不能使用空格**

| 运算符 | 描述                       | 实例                                  |
| ------ | -------------------------- | ------------------------------------- |
| =      | 简单的赋值运算符           | c = a + b 将 a + b 的运算结果赋值为 c |
| +=     | 加法赋值运算符             | c += a 等效于 c = c + a               |
| -=     | 减法赋值运算符             | c -= a 等效于 c = c - a               |
| *=     | 乘法赋值运算符             | c *= a 等效于 c = c * a               |
| /=     | 除法赋值运算符             | c /= a 等效于 c = c / a               |
| //=    | 取整除赋值运算符           | c //= a 等效于 c = c // a             |
| %=     | 取 **模** (余数)赋值运算符 | c %= a 等效于 c = c % a               |
| **=    | 幂赋值运算符               | c **= a 等效于 c = c ** a             |

## 运算优先级

- 以下表格的算数优先级由高到最低顺序排列

| 运算符                   | 描述                   |
| ------------------------ | ---------------------- |
| **                       | 幂 (最高优先级)        |
| * / % //                 | 乘、除、取余数、取整除 |
| + -                      | 加法、减法             |
| <= < > >=                | 比较运算符             |
| == !=                    | 等于运算符             |
| = %= /= //= -= += *= **= | 赋值运算符             |
| not or and               | 逻辑运算符             |



## 不同类型变量之间的运算

- 在 Python 中，两个数字型变量是可以直接进行 算数运算的

- 如果变量是 `bool` 型，在计算时

  - `True` 对应的数字是 `1`
  - `False` 对应的数字是 `0`





