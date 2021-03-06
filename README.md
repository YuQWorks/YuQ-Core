# Yu-Core Java Framework
## 自我介绍
Yu-Core 旨在简化 Java 程序开发难度，与开发过程。  
Yu-Core 将提供非常棒的特性和功能让开发者开发的更加轻松愉快。

虽然不是很想承认，但是我可能还是把它写成了类 Spring 的框架。  
我个人不是很喜欢 Spring，他对我而言太大了。  
而且说实话，Spring 的运行时性能并不优秀，我虽然不能写出来比 Spring 更优秀的框架，但是我能写出来比 Spring 更适合我的框架，也更贴近我心里的那个优秀的框架。

## 功能

* Di  
  * 依赖注入
  * 静态变量依赖注入支持
  * 单例与多例支持
  * BeanFactory 支持
  * Config 指定注入实例支持
* Config
  * 多配置文件支持
  * 多环境配置切换支持
  * 配置项依赖注入支持
* Controller  
  * 完整的路由映射支持
  * 路由上携带参数支持
  * 前置拦截器，后置拦截器，异常拦截器
  * 参数映射
* EventBus
  * 自定义事件
  * 父子事件支持
* Job
  * 异步与等待
  * 定时任务
  * 时钟任务
  * 动态添加与取消
* Class 动态增强
  * 针对特殊场景，对字节码进行优化，减少开发时代码量。
    * Controller 优化
  * 方法 Hook
    * 方法调用前响应
      * 修改参数
      * 取消执行
      * 抛出异常
    * 方法调用后响应
      * 修改返回值
      * 抛出异常
    * 方法异常时响应
      * 取消异常并正常返回
      * 修改异常类型
    * 支持静态与非静态方法
    * 支持 Hook final 类与 final 方法
  * AOP 支持