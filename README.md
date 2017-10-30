# Hibernate

##1.使用maven创建工程

1.点击新建项目
2.选择maven-xxx-webapp
3.选择GroupId和ArtifactId
4.输入工程名
5.finish

## 二.配置pom.xml文件

1.加入struts2的依赖,如下:
```
<!-- https://mvnrepository.com/artifact/org.hibernate/hibernate-core -->
    <dependency>
      <groupId>org.hibernate</groupId>
      <artifactId>hibernate-core</artifactId>
      <version>5.2.10.Final</version>
    </dependency>
```