# xingej-analysis-jdk-concurrent
如何将jdk中关于多线程的源码，导入到intellij idea呢？(window环境)

1、下载JDK源码
  方式一:直接从下面地址中下载(本人就是采用这种方式)
        https://github.com/fanhongtao/JDK
  方式二:从jdk的rt.jar包中获取，例如jdk1.8.0_112\jre\lib\rt.jar
        解压rt.jar
        
 2、利用intellij idea 创建一个普通的java工程
 
 3、拷贝关于多线程的源码，
   注意，拷贝时不要只拷贝java\util\concurrent这个包，
   需要将java 整体包都拷贝到新创建的java工程下，
   这样就可以对JDK源码进行注释，更新，并行可以进行源码的跟踪
   
    
