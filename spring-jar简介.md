# com.netflix.archaius:archaius-core
 * Archaius是Netflix公司开源项目之一，基于java的配置管理类库，主要用于多配置存储的动态获取。
*主要功能是对apache common configuration类库的扩展。在云平台开发中可以将其用作分布式配置管理依赖构件。同时，它*有如下一些特性：
  * 动态类型化属性
  * 高效和线程安全的配置操作
  * 配置改变时的回调机制
  * 轮询框架
  * JMX，通过Jconsole检查和调用操作属性
  * 组合配置
  * [《引用》](https://blog.csdn.net/mzh_cn/article/details/80636718)

# com.netflix.hystrix:hystrix-core
  * Netflix Hystrix是SOA/微服务架构中提供服务隔离、熔断、降级机制的工具/框架。
  * Netflix Hystrix是断路器的一种实现，用于高微服务架构的可用性，是防止服务出现雪崩的利器。
  * [《引用》](https://cloud.tencent.com/developer/article/1333814)
# com.netflix.ribbon:ribbon

# com.netflix.servo:servo-core
  * Netflix Servo 用Java语言，提供暴露、发布应用运行指标的简单接口，
      主要满足的需求包括：使用JMX、简单、灵活发布。
   * [《引用》](https://www.oschina.net/p/netflix-servo)


# org.springframework.boot:spring-boot-starter-actuator
  * 在生产环境中，需要实时或定期监控服务的可用性。
       Spring Boot的actuator（健康监控）功能提供了很多监控所需的接口，
       可以对应用系统进行配置查看、相关功能统计等。
   * [《引用》](https://www.cnblogs.com/EasonJim/p/7613333.html)

#  org.mybatis.spring.boot:mybatis-spring-boot-autoconfigure

   * 自动配置
   * [《引用》](https://blog.csdn.net/seashouwang/article/details/80299571)

# org.springframework.boot:spring-boot-devtools

  * spring-boot-devtools是一个为开发者服务的一个模块，
  * 其中最重要的功能就是自动应用代码更改到最新的App上面去。
  * 原理是在发现代码有更改之后，重新启动应用，但是比速度比手动停止后再启动还要更快，
  * 更快指的不是节省出来的手工操作的时间。其深层原理是使用了两个ClassLoader，
  * 一个Classloader加载那些不会改变的类（第三方Jar包），另一个ClassLoader加载会更改的类，
  * 称为  restart ClassLoader,这样在有代码更改的时候，原来的restartClassLoader 被丢弃，
  * 重新创建一个restartClassLoader，由于需要加载的类相比较少，所以实现了较快的重启时间（5秒以内）。

  * [《引用》](https://blog.csdn.net/seashouwang/article/details/80204283)

