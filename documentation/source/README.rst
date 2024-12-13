.. vim: syntax=rst

关于本eman_clinet指导文档项目
==============

eman_clinet项目的github地址：xxxxxxxxxxx

eman_clinet项目的gitee 地址：xxxxxx

点击右侧链接可在线阅读本eman_clinet指导文档：《 @EasyView Ic Design copyright.man_clinet user guide <https://eman-client-user-guide.readthedocs.io/en/latest/>》


本文档是关于如何使用eman_client编写文档的说明。

eman_client is highly imiatiave sim architure of ic design flow
---------------------------------

eman_client有如下优点：

- 使用extend,abstract 关键字，build section和test section命令选项的继承关系。

- 使用variables来指定build options和sim options，build section和test section 可以通过variablse 可以override build option和override sim option。

- 使用shell进程全程管理所有的build 进程和仿真进程，例如初始化系统环境，以及准备编译前环境，编译后环境，和运行时之前环境，运行时环境，运行时后环境，对环境进行全流程管理。

- 使用json文件存储本地project表、config表、session表、build表、test表、group表，可以通过api上传个人远程服务器热点。

- ....其他优秀的特点
