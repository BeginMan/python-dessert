可迭代对象元素分解，编程中常用的技能， 可迭代对象包括：

- 列表
- 元组
- 字符串
- 文件
- 迭代器
- 生成器

如下：

	>>>a, b, c, d, e = 'Hello'
	>>> b
	'e'

如果舍弃一些变量，如不常用的变量，则可以选择一个不用的变量名，如`_`, 要确保该变量名在其他地方没用到。

	In [11]: a, b, _, _ = 'good'

	In [12]: b
	Out[12]: 'o'

如果可迭代对象元素个数不确定，则使用`*表达式`， 如：

	first, *middle, last = grades

注意，在python3中才支持。

**`*`式语法在变长迭代中经常用到**， 如：

	for a, *args in iterables:
		....
