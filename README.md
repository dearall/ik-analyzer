Long Term Support，welcome pull request

IKAnalyzer 作者林良益 [linliangyi2007@gmail.com](linliangyi2007@gmail.com)，项目网址：[http://code.google.com/p/ik-analyzer/](http://code.google.com/p/ik-analyzer/)

保持 IKAnalyzer 与 Lucene 版本对应，本版本支持 lucene 8.0。

Maven用法：

将以下依赖加入工程的 pom.xml中的依赖部分。

```xml
    <dependency>
        <groupId>org.example.ik-analyzer</groupId>
        <artifactId>ik-analyzer</artifactId>
        <version>8.0.0</version>
    </dependency>
```

安装到本地 Maven 仓库，执行如下命令：

```shell
    mvn clean install -Dmaven.test.skip=true
```
或部署至私有仓库：

```shell
   mvn clean deploy -Dmaven.test.skip=true
```

