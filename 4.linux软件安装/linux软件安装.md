# Linux中的软件安装
#### Linux中,软件包的封装类型多样
- 常见的软件博爱封装类型
    - rpm 扩展名: .rpm
    - deb 扩展名: .deb
    -  源代码软件包 :  扩展名  : .tar.gz 或者.tar.bz2
    -  提供安装程序的软件包 install.sh  , setup , bin
-  rpm软件包包
   -  由redhat公司提出
   -  建立统一的数据库文件,详细记录软件包的安装与卸载,能自动分析软件包的依赖关系.
   -  推荐网站:http://rpmfind.net/
   -  rpm软件包格式:
     
     
     
     
             bash       -5.0        -5.1         i586              .html
            软件名称     版本号      发布次数     硬件平台(noarch)       扩展名

- YUM源软件管理
    - 集中化管理,管理rpm包
    - 很好的解决了软件包之间的依赖关系
    - 