# 目录

* [第1章 语法变迁](ch1/readme.md)
  * [1.1 Go1的诺言](ch1/ch1-1.md)
  * [1.2 Go1到Go1.10](ch1/ch1-2.md)
  * [1.3 Go1.10过渡到Go2](ch1/ch1-3.md)
  * [1.4 Go2诞生](ch1/ch1-4.md)
* [第2章 模块化](ch2/readme.md)
  * [2.1 Go1的包机制(TODO)](ch2/ch2-1.md)
  * [2.2 基于vendor的版本管理(TODO)](ch2/ch2-2.md)
  * [2.3 模块的设计⽬标(TODO)](ch2/ch2-3.md)
  * [2.4 模块快速⼊⻔(TODO)](ch2/ch2-4.md)
  * [2.5 子模块和多版本共存(TODO)](ch2/ch2-5.md)
  * [2.6 镜像和私有仓库(TODO)](ch2/ch2-6.md)
  * [2.7 模块化实践中的一些问题(TODO)](ch2/ch2-7.md)
* [第3章 错误处理(TODO)](ch3/readme.md)


<!--
1.
语言只定义了包的概念
包可以有不同的实现，比如基于zip的包集合

最早是没有gopath的
makefile时代的编译，和goroot是放在一起的
标准库包和用户包的分离

2.
gopath
intrnal
vendor

和std同名的包

3.
vendor的问题
本质原因是不同包中的类型不一样
vendor内的包对应新路径的包

4. 模块的设计⽬标

问题，有时候需要调试，临时修改以来包的代码，
但是修改之后会导致其它依赖此包的应用被影响，可以用replace吗

5. 模块快速⼊⻔
 go mod命令

6. go.mod 和 go.sum⽂件

7. go get重新⼊⻔

8. 语义化版本号

9. v1/v2/v3版本共存

10. ⼦模块

11. 最⼩化版本选择

12. 版本不相容和间接依赖

不相容是历史问题，临时调试修改依赖的包


14. 私有仓库/镜像
以前是每个pkg的go get需要DNS查网址，如果要定制指南修改hosts文件，
但是修改hosts文件将对其它应用产生影响。

-->
