该项目是SpringBoot2.x的项目，项目内集成了很多技术框架。该项目用于快速构建springboot2.x项目，也用于作为自己的知识积累。

ps：不要太在意里面的目录结构，大部分是按照规范来命名和层级关系，但也有一部分只是为了集成在一个项目做备忘用的，所以你们需要根据自己的经验去识别出来
如有不懂的地方，也可以直接通过github issus留言。

具体技术整合请找到springboot的启动类BootApplication，里面通过javadoc的形式说明了目前已集成的技术框架

 <div>
     <p>概要</p>
      <ul>
          <li>整合Redis</li>
          <li>整合了JWT实现token单点登陆，不需要session共享等问题</li>
          <li>有个AOP的小例子</li>
          <li>整合了一个webapp目录用于JSP技术的前端开发</li>
          <li>整合了一个可用的redis分布式可重入防死锁</li>
          <li>整合Spring Session，解决session共享问题</li>
          <li>整合MyBatis以及其逆向工程文件，后续使用了mybatis-plus，对原本项目没有太多影响</li>
          <li>整合rocketmq</li>
      </ul>
  </div>
