# handle-ackage-dependencies
如何处理：无法修正错误,因为您要求某些软件包保持现状,就是它们破坏了软件包间的依赖关系
产生原因：通过apt-get install安装软件或依赖等的时候

使用aptitude进行安装
首先需要安装 aptitude：

sudo apt-get install aptitude
aptitude 安装包：

sudo aptitude install openssh-server
这时 aptitude 会对依赖关系进行智能处理：
