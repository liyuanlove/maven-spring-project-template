Changelog
=========


0.0.4 (2018-06-06)
------------------
- S. [金飞]
- Maven成功执行了一次docker image的构建，将web项目打包好了之后构建成了本地image;将项目结构组织成了多module结构
  ，并建立了子module之间相互调用的测试;加入了maven-enforcer-plugin进行依赖组件的强制检查管理. [金飞]
- 加入了RabbitMQ的使用示例，做了ApplicationRunner和CommandLineRunner的测试示例，测试了使用@Orde
  r设置多个Runner的执行顺序. [金飞]
- 试了试OrientDB的增删改查，做了Todo的api. [金飞]
- S. [金飞]
- S. [ascode]


0.0.3 (2018-05-30)
------------------
- 修改了版本号. [ascode]
- 因为Maven库上找不到springcloud官网示例的jar版本，所以暂时搁置了融入springcloud,并选型了连接orientdb图
  库的方式. [ascode]
- 还是暂时放弃融入spring cloud. [ascode]
- S. [ascode]


0.0.2 (2018-05-30)
------------------
- 框架中加入了hibernate. [ascode]
- S. [ascode]
- Initial commit. [金飞]
- S. [ascode]


