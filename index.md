## Welcome to Zhang's blog.

一入IT深似海，不忘初心不负卿

### struts2配置文件的加载顺序和优先级

1.优先级
        web.xml > struts.properties > struts.xml > default.properties


 2.加载顺序
        1.default.properties文件 
        作用:定义了struts2框架中所有常量 
        位置: org/apache/struts2/default.properties

        2.struts-default.xml 
        作用:配置了bean,interceptor,result等。 
        位置:在struts的core核心jar包. 
        
        struts-plugin.xml 
        它是struts2框架中所使用的插件的配置文件。
        
        struts.xml 
        我们使struts2所使用的配置文件。
        
        3.struts.properties 
        就是可以自定义常量。
        
        4.web.xml
--------------------- 
作者：20508LAlala 
原文：https://blog.csdn.net/zx_balabala/article/details/82817428 

### java中方法和函数区别

面向对象的语言叫方法

面向过程的语言叫函数

在java中没有函数这么一说，只有方法一说。实际上方法就是函数，函数就是方法，只是在不同的语言不同的称呼而已。

 

一句话告诉你如何区分函数与方法：函数是大家的函数，方法是类的方法。
如何区分一个ITer是设计师还是码工。
看看他是在调别人的库，还是自己写出JAR包跟别人分享。
感觉差的不是一个级别而已啊。
一个东西，用对象调用的叫方法，直接调函数名的叫函数。
c语言等语言里叫函数，面向对象编程，函数写到类里边就叫做方法，函数可以直接调用，对象中的方法一般都有指针this指向它，但是有时一些方法实在不需要写到类里边，所以面向对象的语言有了静态方法，不过这个概念没必要纠结，用的多了自然就明白啦
函数Function, 过程Procedure, 方法Method，你可以简单把他们当成同一个概念：都是由若干语句组成的一个可执行代码体。
函数：Function（面向过程语言教程的英文原版，是否有一个把Function翻译为Method的？）
方法：Method（只有不地道的面向对象语言教程才会把Method叫做Function）
意思一样的，可能就是方法偏重于类，也就是面向对象设计的，注重每个函数的功能所以叫方法；而函数偏重于面向过程，有可能是功能描述也有能不是，两者都有是看编程者自己怎么看的
--------------------- 
作者：20508LAlala  
原文：https://blog.csdn.net/zx_balabala/article/details/82633975 

### idea实现阿里云短信发送----JAVA学习

作者：20508LAlala 
原文：https://blog.csdn.net/zx_balabala/article/details/82561265 

### CentOS7安装mysql提示“No package mysql-server available

原因是：

CentOS7带有MariaDB而不是MySQL，MariaDB和MySQL一样也是开元的数据库，
您可以使用yum -y install mariadb-server mariadb命令安装

解决方案：

如果必须要安装MySQL，首先必须添加mysql社区repo通过输入命令：
    sudo rpm -Uvh http://dev.mysql.com/get/mysql-community-release-el7-5.noarch.rpm，
最后使用像安装MySQL的常规方法一样安装mysql：
    yum install mysql mysql-server mysql-libs mysql-server             
--------------------- 
作者：20508LAlala 
原文：https://blog.csdn.net/zx_balabala/article/details/82227996 

### idea文件上传功能的实现

作者：20508LAlala 
原文：https://blog.csdn.net/zx_balabala/article/details/81736026 




