# <img src="src/docs/asciidoc/images/spring-framework.png" width="80" height="80"> Spring Framework [![Build Status](https://ci.spring.io/api/v1/teams/spring-framework/pipelines/spring-framework-5.2.x/jobs/build/badge)](https://ci.spring.io/teams/spring-framework/pipelines/spring-framework-5.2.x?groups=Build")

This is the home of the Spring Framework: the foundation for all [Spring projects](https://spring.io/projects). Collectively the Spring Framework and the family of Spring projects are often referred to simply as "Spring". 

Spring provides everything required beyond the Java programming language for creating enterprise applications for a wide range of scenarios and architectures. Please read the [Overview](https://docs.spring.io/spring/docs/current/spring-framework-reference/overview.html#spring-introduction) section as reference for a more complete introduction.

## Code of Conduct

This project is governed by the [Spring Code of Conduct](CODE_OF_CONDUCT.adoc). By participating, you are expected to uphold this code of conduct. Please report unacceptable behavior to spring-code-of-conduct@pivotal.io.

## Access to Binaries

For access to artifacts or a distribution zip, see the [Spring Framework Artifacts](https://github.com/spring-projects/spring-framework/wiki/Spring-Framework-Artifacts) wiki page.

## Documentation

The Spring Framework maintains reference documentation ([published](https://docs.spring.io/spring-framework/docs/current/spring-framework-reference/) and [source](src/docs/asciidoc)), Github [wiki pages](https://github.com/spring-projects/spring-framework/wiki), and an
[API reference](https://docs.spring.io/spring-framework/docs/current/javadoc-api/). There are also [guides and tutorials](https://spring.io/guides) across Spring projects.

## Build from Source

See the [Build from Source](https://github.com/spring-projects/spring-framework/wiki/Build-from-Source) Wiki page and the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## Stay in Touch

Follow [@SpringCentral](https://twitter.com/springcentral), [@SpringFramework](https://twitter.com/springframework), and its [team members](https://twitter.com/springframework/lists/team/members) on Twitter. In-depth articles can be found at [The Spring Blog](https://spring.io/blog/), and releases are announced via our [news feed](https://spring.io/blog/category/news).

## License

The Spring Framework is released under version 2.0 of the [Apache License](https://www.apache.org/licenses/LICENSE-2.0).

## 阅读 Spring Framework 的源码，建议按照以下顺序进行：
1. Core Container 模块：这是 Spring Framework 的核心模块，包括 IoC 和 DI 的实现，提供了控制反转和依赖注入的功能。可以从 BeanFactory 和 ApplicationContext 接口开始阅读。

2. Spring AOP 模块：这个模块提供了面向切面编程的实现，可以从 AOP Alliance 接口开始阅读。

3. Spring JDBC 模块：这个模块提供了简单的 JDBC 操作封装，可以从 JdbcTemplate 类开始阅读。

4. Spring ORM 模块：这个模块提供了对 ORM 框架的集成支持，可以从 HibernateTemplate 或 JpaTemplate 类开始阅读。

5. Spring Web 模块：这个模块提供了 Web 应用开发的支持，包括 MVC 框架、远程调用、安全性等，可以从 DispatcherServlet 类开始阅读。

6. Spring Test 模块：这个模块提供了对测试的支持，包括单元测试和集成测试，可以从 AbstractJUnit4SpringContextTests 类开始阅读。

以上是建议的阅读顺序，当然也可以根据自己的需求和兴趣选择不同的模块进行阅读。同时，建议结合官方文档和源码注释来阅读源码，这样更有助于理解代码的实现。