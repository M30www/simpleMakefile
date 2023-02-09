# simpleMakefile
a simple try about how to write a makefile
通过四个版本：
version 1
单纯把编译链接命令放进makefile
version 2
将编译命令 - 编译目标 - obj文件 分开，并分开编译cpp文件（单一cpp文件更改只需单独编译，文件增删仍需更改）
version3
将编译命令 - 参数 - obj文件分开，且自动匹配编译对应的obj、cpp文件，增加了clean，但新增文件仍需手动添加
version4
同上，自动载入cpp文件，自动生成obj目标，新增文件时不需要手动添加，自动索引
