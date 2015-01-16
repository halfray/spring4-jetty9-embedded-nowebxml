jetty9 Spring4 Embedded NoWebXML Example
==============================
利用jetty9启动无web.xml配置的spring4最简单应用程序

Requirements
------------
* [Java Platform (JDK) 7](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
* [Apache Maven 3.x](http://maven.apache.org/)

# 启动应用程序的方法
方法1
-----------
1. `mvn jetty:run`
方法2
-----------
2.  `mvn clean install exec:exec`
方法3
-----------
1. 通过jetty的 `org.eclipse.jetty.xml.XmlConfiguration` 执行jetty/jetty.xml文件
方法4
-----------
1. 执行`com.halfray.example.initializer.JettyWebContextServer`类的`main`方法
方法5
-----------
1. 执行`com.halfray.example.initializer.JettyServletContextServer`类的`main`方法

# 通过浏览器查看应用
[http://localhost:8080/](http://localhost:8080/)
