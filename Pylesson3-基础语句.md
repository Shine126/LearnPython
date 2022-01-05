
### 条件语句
1. if - elif - else 语句
>if expression1:
    expr1_true_suite
elif expression2:
    expr2_true_suite
    .
    .
elif expressionN:
    exprN_true_suite
else:
    expr_false_suite

2. assert 关键词
* assert这个关键词我们称之为“断言”，当这个关键词后边的条件为 False 时，程序自动崩溃并抛出AssertionError的异常。
> assert 3 > 7
#AssertionError

### 循环语句
1. while - else 循环
>while 布尔表达式:
    代码块
else:
    代码块

2. for - else 循环
>for 迭代变量 in 可迭代对象:
    代码块
else:
    代码块

3. range() 函数
range([start,] stop[, step=1])
* 这个BIF（Built-in functions）有三个参数，其中用中括号括起来的两个表示这两个参数是可选的。
* step=1 表示第三个参数的默认值是1。
* range 这个BIF的作用是生成一个从start参数的值开始到stop参数的值结束的数字序列，该序列包含start的值但不包含stop的值。

4. enumerate()函数
enumerate(sequence, [start=0])
* sequence：一个序列、迭代器或其他支持迭代对象。
* start：下标起始位置。
* 返回 enumerate(枚举) 对象

5. break 语句
break语句可以跳出当前所在层的循环。
6. continue 语句
continue终止本轮循环并开始下一轮循环。

7. pass 语句
pass 语句的意思是“不做任何事”，如果你在需要有语句的地方不写任何语句，那么解释器会提示出错，而 pass 语句就是用来解决这些问题的
8. 推导式
[ expr for value in collection [if condition] ]
>x = [-4, -2, 0, 2, 4]
y = [a * 2 for a in x]
print(y)
>[-8, -4, 0, 4, 8]

