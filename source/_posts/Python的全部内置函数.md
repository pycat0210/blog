---
title: Python的全部内置函数
date: 2025-05-14 00:51:15
tags:
    - 编程
    - Python
---

# Python的全部内置函数

转载自 [Python 的内建函数](https://gist.github.com/hubenchang0515/e5d7c948f33b3bcb1155bbe64f769c9f)

| 函数名                | 详细                                                                   | 简介                                                      |                                           
| :-                    | :-                                                                     | :-                                                        |
| `abs`                 | [abs](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.abs.md)              | 计算绝对值                                                | 
| `aiter`               | [aiter](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.aiter.md)            | 获取异步可迭代对象的迭代器                                |               
| `all`                 | [all](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.all.md)              | 判断可迭代对象内容是否全部为真值                          |
| `anext`               | [anext](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.anext.md)            | 获取异步迭代器的下一数据项                                |
| `any`                 | [any](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.any.md)              | 判断可迭代对象内容是否存在真值                            |
| `ascii`               | [ascii](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.ascii.md)            | 转换为字符串，非 ASCII 字符将被转义                       |
| `bin`                 | [bin](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.bin.md)              | 将一个整数转换为带前缀 `0b` 的二进制数字符串              | 
| `bool`                | [bool](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.bool.md)             | 类型转换为 `bool`                                         | 
| `breakpoint`          | [breakpoint](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.breakpoint.md)       | 调用位置进入调试器                                        | 
| `bytearray`           | [bytearray](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.bytearray.md)        | 类型转换为 `bytearray`                                    | 
| `bytes`               | [bytes](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.bytes.md)            | 类型转换为 `bytes`                                        | 
| `callable`            | [callable](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.callable.md)         | 判断对象是否可调用                                        | 
| `chr`                 | [chr](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.chr.md)              | 单个 Unicode 字符的整数编码转字符串                       | 
| `classmethod`         | [classmethod](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.classmethod.md)      | 把一个方法封装成类方法                                    | 
| `compile`             | [compile](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.compile.md)          | 将 source 编译成代码或 AST 对象                           | 
| `complex`             | [complex](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.complex.md)          | 类型转换为 `complex`                                      | 
| `delattr`             | [delattr](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.delattr.md)          | 删除指定的属性                                            | 
| `dict`                | [dict](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.dict.md)             | 类型转换为 `dict`                                         | 
| `dir`                 | [dir](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.dir.md)              | 返回当前本地作用域中的名称列表或对象的属性列表            | 
| `divmod`              | [divmod](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.divmod.md)           | 返回整数除法时的商和余数                                  | 
| `enumerate`           | [enumerate](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.enumerate.md)        | 返回一个枚举对象                                          | 
| `eval`                | [eval](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.eval.md)             | 执行表达式并返回结果                                      | 
| `exec`                | [exec](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.exec.md)             | 执行代码                                                  | 
| `filter`              | [filter](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.filter.md)           | 过滤数据                                                  | 
| `float`               | [float](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.float.md)            | 类型转换为 `float`                                        | 
| `format`              | [format](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.format.md)           | 格式化                                                    | 
| `frozenset`           | [frozenset](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.frozenset.md)        | 类型转换为 `frozenset`                                    | 
| `getattr`             | [getattr](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.getattr.md)          | 获取属性的值                                              | 
| `globals`             | [globals](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.globals.md)          | 返回实现当前模块命名空间的字典                            | 
| `hasattr`             | [hasattr](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.hasattr.md)          | 判断属性是否存在                                          | 
| `hash`                | [hash](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.hash.md)             | 获取哈希值                                                | 
| `help`                | [help](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.help.md)             | 启动内置的帮助系统                                        | 
| `hex`                 | [hex](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.hex.md)              | 将整数转换为带前缀 `0x` 前缀的小写十六进制数字符串        | 
| `id`                  | [id](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.id.md)               | 返回对象的 ID                                             | 
| `input`               | [input](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.input.md)            | 获取输入                                                  | 
| `int`                 | [int](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.int.md)              | 类型转换为 `int`                                          | 
| `isinstance`          | [isinstance](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.isinstance.md)       | 判断是否是某个类型的实例                                  | 
| `issubclass`          | [issubclass](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.issubclass.md)       | 判断是否是某个类的子类                                    | 
| `iter`                | [iter](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.iter.md)             | 获取迭代器                                                | 
| `len`                 | [len](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.len.md)              | 获取长度                                                  | 
| `list`                | [list](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.list.md)             | 类型转换为 `list`                                         | 
| `locals`              | [locals](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.locals.md)           | 返回一个代表当前局部符号表的映射对象                      | 
| `map`                 | [map](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.map.md)              | 将可迭代对象进行映射                                      | 
| `max`                 | [max](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.max.md)              | 获取最大值                                                | 
| `memoryview`          | [memoryview](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.memoryview.md)       | 返回由给定实参创建的“内存视图”对象                        | 
| `min`                 | [min](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.min.md)              | 获取最小值                                                | 
| `next`                | [next](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.next.md)             | 获取迭代器的下一个元素                                    | 
| `object`              | [object](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.object.md)           | 所有类的终极基类，调用时构建一个基本对象                  | 
| `oct`                 | [oct](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.oct.md)              | 将整数转换为带前缀 `0o` 的八进制数字符串                  | 
| `open`                | [open](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.open.md)             | 打开文件                                                  | 
| `ord`                 | [ord](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.ord.md)              | 单个 Unicode 字符的字符串转整数编码                       | 
| `pow`                 | [pow](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.pow.md)              | 计算乘方                                                  | 
| `print`               | [print](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.print.md)            | 打印                                                      | 
| `property`            | [property](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.property.md)         | 创建属性                                                  | 
| `range`               | [range](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.range.md)            | 生成范围序列                                              | 
| `repr`                | [repr](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.repr.md)             | 转换为字符串                                              | 
| `reversed`            | [reversed](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.reversed.md)         | 迭代器逆转                                                | 
| `round`               | [round](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.round.md)            | 四舍五入                                                  | 
| `set`                 | [set](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.set.md)              | 类型转换为 `set`                                          | 
| `setattr`             | [setattr](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.setattr.md)          | 设置属性的值                                              | 
| `slice`               | [slice](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.slice.md)            | 生成切片                                                  | 
| `sorted`              | [sorted](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.sorted.md)           | 排序                                                      | 
| `staticmethod`        | [staticmethod](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.staticmethod.md)     | 将方法转换为静态方法                                      | 
| `str`                 | [str](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.str.md)              | 类型转换为 `str`                                          | 
| `sum`                 | [sum](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.sum.md)              | 求和                                                      | 
| `super`               | [super](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.super.md)            | 获取父类                                                  | 
| `tuple`               | [tuple](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.tuple.md)            | 类型转换为 `tuple`                                        | 
| `type`                | [type](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.type.md)             | 获取类型                                                  | 
| `vars`                | [vars](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.vars.md)             | 获取对象的属性列表                                        | 
| `zip`                 | [zip](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.zip.md)              | 多个迭代器组合成元组迭代器                                | 
| `__import__`          | [__import__](https://xplanc.org/primers/document/zh/02.Python/EX.内建函数.hide/EX.__import__.md)       | 导入模块                                                  | 
