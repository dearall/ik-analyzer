Long Term Support，welcome pull request

IKAnalyzer 作者林良益 [linliangyi2007@gmail.com](linliangyi2007@gmail.com)，项目网址：[http://code.google.com/p/ik-analyzer/](http://code.google.com/p/ik-analyzer/)

保持 IKAnalyzer 与 Lucene 版本对应，本版本支持 lucene 版本：
8.0/8.1/8.2/8.3/8.4/8.5/8.6/8.7/8.8/8.9/8.10/8.11/9.0/9.1/9.2/9.3

- Solr 支持: [https://github.com/magese/ik-analyzer-solr](https://github.com/magese/ik-analyzer-solr)
- Elasticsearch 支持：[https://github.com/medcl/elasticsearch-analysis-ik](https://github.com/medcl/elasticsearch-analysis-ik)

Maven用法：

将以下依赖加入工程的 pom.xml中的依赖部分。

```xml
    <dependency>
        <groupId>org.example.ik-analyzer</groupId>
        <artifactId>ik-analyzer</artifactId>
        <version>9.3</version>
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

