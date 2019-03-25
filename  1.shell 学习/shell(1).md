# shell 学习
**在Linux当中严格区分大小写** 
 **在Linux中一切皆文本**
## shell的定义
- 概念：shell是一种特殊的程序。
- 作用：是内核与用户的一种接口
- shell命令解释器
    - 是一种解释型的语言，分为内部命令和外部命令
    - 内部命令：系统自带的，随系统一起启动。    Eg： cd（改变路径）
    - 外部命令：一些额外的软件或者程序。    Eg： ls（列出文件或者目录）   
## shell介绍（BASH，自带的一种shell）
- su - root： 可以切换普通用户和root用户
    - su passwd root： 可以改变root用户密码
    - su - 用户名：可以切换到其他用户
    - 其中的 - 表示切换bash环境
    - \# 表示root用户
    - $ 表示普通用户
- exit：退出当前用户
- 查看系统当前主机名： hostname
- 修改主机名：hostnamectl set-hostname ”主机名“
- 关机命令
    - poweroff
    - init 0
    - shutdown -r now #现在重启
    - shutdown -r +15 #15min后重启
- 准确的shell命令：
    - 命令字 [选项] 参数
- 查看系统时间：date
- 查看系统日历：cal
    - cal 年份：查看全年日历
    - cal 月份 年份：查看某年某月日历























