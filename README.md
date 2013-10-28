huffuman-compress
=================

一个基于huffuman编码的文件压缩算法


编码示例:
./a.out [-enc] input [-o output] [-tf output.enc]

解码示例:
./a.out [-dec] input [-o output] [-tf input.enc]

参数解释:
-enc : 编码
-dec : 解码
-o   : 输出的文件名
-tf  : 中间文件, 存储字符对应的huffuman编码, 解码依赖于此文件.
