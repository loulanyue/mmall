maven的pom文件

    properties	pom配置
    project.build.sourceEncoding	UTF-8
    project.reporting.outputEncoding	UTF-8
    maven.compiler.encoding	UTF-8
    ${org.springframework.version}	4.0.0.RELEASE
    ${org.mybatis.spring.version}	3.4.1
    ${org.mybatis.version}	1.30

    dependencies	依赖
    tomcat-servlet-api	7.0.64
    spring-webmvc	${org.springframework.version}
    spring-oxm	${org.springframework.version}
    spring-jdbc	${org.springframework.version}
    spring-tx	${org.springframework.version}
    spring-test	${org.springframework.version}
    aspectiweaver	1.7.3 (AOP使用)
    mybatis-spring	${org.mybatis.spring.version}
    mybatis	${org.mybatis.version}
    aspectjrt	1.6.11(AOP使用)
    jackson-mapper-asl	1.9.12(json序列化和反序列化)
    commons-dbcp	1.4 连接池
    logback-classic	1.1.2(日志)
    logback-core	1.1.2(日志)
    mysql-connector-java	5.1.6(mysql连接池)
    guava	20.0(各种丰富的工具类和数据结构)
    commons-lang3	3.5(apache工具类)
    commons-collections	3.2.1(集合工具类)
    junit	4.12(单元测试)
    joda-time	2.3(时间处理)
    hashids	1.0.1(id加解密的jar包)
    commons-net	3.1(ftp服务器client的jar包)
    commons-fileupload	1.2.2(上传文件)
    commons-io	2.0.1(上传文件)
    pagehelper	4.1.0(mybatis分页插件)
    mybatis-paginator	1.2.17(mybatis分页插件)
    jsqlparser	0.9.4(mybatis分页插件)
    commons-codec	1.10(支付宝jar包)
    commons-configuratioin	1.10
    commons-lang	2.6
    commons-logging	1.1.1
    core	2.1
    gson	2.3.1
    hamcrest-core	1.3

    build	plugin
    mybatis-generator-maven-plugin	1.3.2
    maven-compiler-plugin	引入本地jar包 ${project.basedir}/scr/main/webapp/WEB-INF/lib
