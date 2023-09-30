# Java21-for-backend-developers-code
《写给后端开发者的Java21手册》源码项目

Java21下载地址：https://jdk.java.net/21/
大部分demo都是基于Java21构建的单文件程序，如果当前IDE不支持运行，可以使用命令行编译运行。
命令行编译运行示例：
```
/{java21-path}/jdk-21.jdk/Contents/Home/bin/java --enable-preview --release 21 XXX.java
```

1 虚拟线程
---

* VTread

2 并发编程
---

* Flow 9+
* StructuredTaskScope 21+
* ScopedValue 21+
* org.openjdk.jmh 12+不需要额外jar，12以下需要手动引入

3 类型系统更新
---

* var 9+
* 记录类 21+
* 密封类 17+
* Value-based Classes 
* Hidden Classes 11+
* class nests 11+
* Method Handles 18+

4 流程控制与模式匹配
---

* switch
* instant of

5 字符串
---

* StrTemplate
* TextBlock

6 集合、网络、监控
---

* CollectionFactoryMethods 9+
* jfr 9+ jfr.stream 14+ jfr.network.stream 16+
* HttpClient 11+
* SequencedMap 21+

7 模块系统变更
---

无代码示例

8 Java在垃圾回收领域的变化
---

无代码示例

9 其他重要更新
---

* LOG 9+
* DeserializationFilter 9+ 
* EdDSA 
* ForeignFuncMemAPI 19+ 20+
* RandomGenerator 17+
* StackWalker 9+

10 Java研发效能、脚本
---

* java --source执行源码
* jshell执行脚本