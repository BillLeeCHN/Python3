# 《Python入门教程》

# 第一章 数字
# 1.1 Integers

## 1.1.1 加
```python
2+3
```
## 1.1.2 减
```python
2-3
```
## 1.1.3 乘
```python
2 * 3
```
## 1.1.4 除
```python
2 / 3 # 0.6666666666666666
2 //3 # 0
```
## 1.1.5 幂指数
```python
2 ** 5 # 32
```
## 1.1.6 取余
```python
111 % 2 # 1
```
## 1.1.7 赋值
```python
a = 2
```
## 1.1.8 变量类型
```python
a = 1
type(a)
```
## 1.1.9 获得Integer的取值范围
```python
import sys
sys.maxint
```

# 1.2 float
## 1.2.1 获得类型
```python
a = 1.5
type(a) # float
```
## 1.2.2 控制小数点数量
```python
'{:.52}'.format(3.4 - 3.2)

#output
'-0.100000000000000088817841970012523233890533447265625'
```
## 1.2.3 获得浮点数最大数
```python
import sys
sys.float_info.max
```
## 1.2.4 获得浮点数最小值
```python
import sys
sys.float_info.min
```
## 1.2.5 浮点数精度
```python
import sys
sys.float_info.epsilon # 2.220446049250313e-16
```

# 1.3 复数 complex numbers
## 1.3.1 表示
Python 使用 j 来表示复数的虚部：
```python
a = 1 + 2j
```
## 1.3.2 实部
```python
a.real
```
## 1.3.3 虚部
```python
a.imag
```
## 1.3.4 共轭
```python
a.conjugate() # 1-2j
```

# 1.4 优先级
```
( ) 括号
** 幂指数运算
* / // % 乘，除，整数除法，取余运算
'+ -' 加减
```
# 1.5 built_in functions
```python
abs()
round() # 四舍五入
min()
max()
```
# 1.6 类型转换
## 1.6.1 float -> int
```python
int(12.3) # 12
int(-3.2) # -3
```
## 1.6.2 int -> float
```python
float(2)
```
# 1.7 整数的表示方法
## 1.7.1 十进制
```python
12
```
## 1.7.2 科学计数法
```python
1e-9 # 1e-09
```
## 1.7.3 十六进制
```python
oxFF
```
## 1.7.4 八进制
前面加```0o```,后面加上0-7之间的数
```python
0o45
```
## 1.7.5 二进制
前面加```0b```,后面加0,1
```python
0b10101
```
## 1.7.6 不同进制之间转换
```python
hex(255) # '0xff'
oct(255) # '0o377'
bin(255) # '0b11111111'

int('12') # 12
float('12.3') # 12.3

int('FF',16)
int('377',8)
int('11111',2)
```

# 1.8 布尔boolean
```python
b = True
type(b) # bool
```
# 1.9 链式比较
```python
1 < x <= 3
```
