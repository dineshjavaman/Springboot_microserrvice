"C:\Program Files\Java\jdk-11.0.13\bin\java.exe" -agentlib:jdwp=transport=dt_socket,address=127.0.0.1:60140,suspend=y,server=n -javaagent:C:\Users\DINESH\AppData\Local\JetBrains\IdeaIC2021.3\captureAgent\debugger-agent.jar -Dfile.encoding=UTF-8 -classpath "E:\Workspace\SPRINGBOOT_microserrvice\target\classes;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-starter-data-jpa\2.6.4\spring-boot-starter-data-jpa-2.6.4.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-starter-aop\2.6.4\spring-boot-starter-aop-2.6.4.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-aop\5.3.16\spring-aop-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\aspectj\aspectjweaver\1.9.7\aspectjweaver-1.9.7.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-starter-jdbc\2.6.4\spring-boot-starter-jdbc-2.6.4.jar;C:\Users\DINESH\.m2\repository\com\zaxxer\HikariCP\4.0.3\HikariCP-4.0.3.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-jdbc\5.3.16\spring-jdbc-5.3.16.jar;C:\Users\DINESH\.m2\repository\jakarta\transaction\jakarta.transaction-api\1.3.3\jakarta.transaction-api-1.3.3.jar;C:\Users\DINESH\.m2\repository\jakarta\persistence\jakarta.persistence-api\2.2.3\jakarta.persistence-api-2.2.3.jar;C:\Users\DINESH\.m2\repository\org\hibernate\hibernate-core\5.6.5.Final\hibernate-core-5.6.5.Final.jar;C:\Users\DINESH\.m2\repository\org\jboss\logging\jboss-logging\3.4.3.Final\jboss-logging-3.4.3.Final.jar;C:\Users\DINESH\.m2\repository\net\bytebuddy\byte-buddy\1.11.22\byte-buddy-1.11.22.jar;C:\Users\DINESH\.m2\repository\antlr\antlr\2.7.7\antlr-2.7.7.jar;C:\Users\DINESH\.m2\repository\org\jboss\jandex\2.4.2.Final\jandex-2.4.2.Final.jar;C:\Users\DINESH\.m2\repository\com\fasterxml\classmate\1.5.1\classmate-1.5.1.jar;C:\Users\DINESH\.m2\repository\org\hibernate\common\hibernate-commons-annotations\5.1.2.Final\hibernate-commons-annotations-5.1.2.Final.jar;C:\Users\DINESH\.m2\repository\org\glassfish\jaxb\jaxb-runtime\2.3.6\jaxb-runtime-2.3.6.jar;C:\Users\DINESH\.m2\repository\org\glassfish\jaxb\txw2\2.3.6\txw2-2.3.6.jar;C:\Users\DINESH\.m2\repository\com\sun\istack\istack-commons-runtime\3.0.12\istack-commons-runtime-3.0.12.jar;C:\Users\DINESH\.m2\repository\com\sun\activation\jakarta.activation\1.2.2\jakarta.activation-1.2.2.jar;C:\Users\DINESH\.m2\repository\org\springframework\data\spring-data-jpa\2.6.2\spring-data-jpa-2.6.2.jar;C:\Users\DINESH\.m2\repository\org\springframework\data\spring-data-commons\2.6.2\spring-data-commons-2.6.2.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-orm\5.3.16\spring-orm-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-context\5.3.16\spring-context-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-tx\5.3.16\spring-tx-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-beans\5.3.16\spring-beans-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\slf4j\slf4j-api\1.7.36\slf4j-api-1.7.36.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-aspects\5.3.16\spring-aspects-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-starter-web\2.6.4\spring-boot-starter-web-2.6.4.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-starter\2.6.4\spring-boot-starter-2.6.4.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot\2.6.4\spring-boot-2.6.4.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-autoconfigure\2.6.4\spring-boot-autoconfigure-2.6.4.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-starter-logging\2.6.4\spring-boot-starter-logging-2.6.4.jar;C:\Users\DINESH\.m2\repository\ch\qos\logback\logback-classic\1.2.10\logback-classic-1.2.10.jar;C:\Users\DINESH\.m2\repository\ch\qos\logback\logback-core\1.2.10\logback-core-1.2.10.jar;C:\Users\DINESH\.m2\repository\org\apache\logging\log4j\log4j-to-slf4j\2.17.1\log4j-to-slf4j-2.17.1.jar;C:\Users\DINESH\.m2\repository\org\apache\logging\log4j\log4j-api\2.17.1\log4j-api-2.17.1.jar;C:\Users\DINESH\.m2\repository\org\slf4j\jul-to-slf4j\1.7.36\jul-to-slf4j-1.7.36.jar;C:\Users\DINESH\.m2\repository\jakarta\annotation\jakarta.annotation-api\1.3.5\jakarta.annotation-api-1.3.5.jar;C:\Users\DINESH\.m2\repository\org\yaml\snakeyaml\1.29\snakeyaml-1.29.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-starter-json\2.6.4\spring-boot-starter-json-2.6.4.jar;C:\Users\DINESH\.m2\repository\com\fasterxml\jackson\core\jackson-databind\2.13.1\jackson-databind-2.13.1.jar;C:\Users\DINESH\.m2\repository\com\fasterxml\jackson\core\jackson-annotations\2.13.1\jackson-annotations-2.13.1.jar;C:\Users\DINESH\.m2\repository\com\fasterxml\jackson\core\jackson-core\2.13.1\jackson-core-2.13.1.jar;C:\Users\DINESH\.m2\repository\com\fasterxml\jackson\datatype\jackson-datatype-jdk8\2.13.1\jackson-datatype-jdk8-2.13.1.jar;C:\Users\DINESH\.m2\repository\com\fasterxml\jackson\datatype\jackson-datatype-jsr310\2.13.1\jackson-datatype-jsr310-2.13.1.jar;C:\Users\DINESH\.m2\repository\com\fasterxml\jackson\module\jackson-module-parameter-names\2.13.1\jackson-module-parameter-names-2.13.1.jar;C:\Users\DINESH\.m2\repository\org\springframework\boot\spring-boot-starter-tomcat\2.6.4\spring-boot-starter-tomcat-2.6.4.jar;C:\Users\DINESH\.m2\repository\org\apache\tomcat\embed\tomcat-embed-core\9.0.58\tomcat-embed-core-9.0.58.jar;C:\Users\DINESH\.m2\repository\org\apache\tomcat\embed\tomcat-embed-el\9.0.58\tomcat-embed-el-9.0.58.jar;C:\Users\DINESH\.m2\repository\org\apache\tomcat\embed\tomcat-embed-websocket\9.0.58\tomcat-embed-websocket-9.0.58.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-web\5.3.16\spring-web-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-webmvc\5.3.16\spring-webmvc-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-expression\5.3.16\spring-expression-5.3.16.jar;C:\Users\DINESH\.m2\repository\com\h2database\h2\1.4.200\h2-1.4.200.jar;C:\Users\DINESH\.m2\repository\jakarta\xml\bind\jakarta.xml.bind-api\2.3.3\jakarta.xml.bind-api-2.3.3.jar;C:\Users\DINESH\.m2\repository\jakarta\activation\jakarta.activation-api\1.2.2\jakarta.activation-api-1.2.2.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-core\5.3.16\spring-core-5.3.16.jar;C:\Users\DINESH\.m2\repository\org\springframework\spring-jcl\5.3.16\spring-jcl-5.3.16.jar;C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2021.3.1\lib\idea_rt.jar" com.Springboot_Microservice.Springboot_Microservice.SpringbootMicroserviceApplication
Connected to the target VM, address: '127.0.0.1:60140', transport: 'socket'

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::                (v2.6.4)

2022-03-22 23:58:43.079  INFO 14176 --- [           main] c.S.S.SpringbootMicroserviceApplication  : Starting SpringbootMicroserviceApplication using Java 11.0.13 on DESKTOP-7QDDIVK with PID 14176 (E:\Workspace\SPRINGBOOT_microserrvice\target\classes started by DINESH in E:\Workspace\SPRINGBOOT_microserrvice)
2022-03-22 23:58:43.095  INFO 14176 --- [           main] c.S.S.SpringbootMicroserviceApplication  : No active profile set, falling back to 1 default profile: "default"
2022-03-22 23:58:45.751  INFO 14176 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
2022-03-22 23:58:45.891  INFO 14176 --- [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 108 ms. Found 1 JPA repository interfaces.
2022-03-22 23:58:48.516  INFO 14176 --- [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port(s): 8080 (http)
2022-03-22 23:58:48.579  INFO 14176 --- [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2022-03-22 23:58:48.579  INFO 14176 --- [           main] org.apache.catalina.core.StandardEngine  : Starting Servlet engine: [Apache Tomcat/9.0.58]
2022-03-22 23:58:49.001  INFO 14176 --- [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2022-03-22 23:58:49.001  INFO 14176 --- [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 5641 ms
2022-03-22 23:58:49.188  WARN 14176 --- [           main] ConfigServletWebServerApplicationContext : Exception encountered during context initialization - cancelling refresh attempt: org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'dataSourceScriptDatabaseInitializer' defined in class path resource [org/springframework/boot/autoconfigure/sql/init/DataSourceInitializationConfiguration.class]: Unsatisfied dependency expressed through method 'dataSourceScriptDatabaseInitializer' parameter 0; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'dataSource' defined in class path resource [org/springframework/boot/autoconfigure/jdbc/DataSourceConfiguration$Hikari.class]: Bean instantiation via factory method failed; nested exception is org.springframework.beans.BeanInstantiationException: Failed to instantiate [com.zaxxer.hikari.HikariDataSource]: Factory method 'dataSource' threw exception; nested exception is java.lang.IllegalStateException: Cannot load driver class: org.h2.Driver  
2022-03-22 23:58:49.204  INFO 14176 --- [           main] o.apache.catalina.core.StandardService   : Stopping service [Tomcat]
2022-03-22 23:58:49.376  INFO 14176 --- [           main] ConditionEvaluationReportLoggingListener : 

Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
2022-03-22 23:58:49.438 ERROR 14176 --- [           main] o.s.boot.SpringApplication               : Application run failed

org.springframework.beans.factory.UnsatisfiedDependencyException: Error creating bean with name 'dataSourceScriptDatabaseInitializer' defined in class path resource [org/springframework/boot/autoconfigure/sql/init/DataSourceInitializationConfiguration.class]: Unsatisfied dependency expressed through method 'dataSourceScriptDatabaseInitializer' parameter 0; nested exception is org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'dataSource' defined in class path resource [org/springframework/boot/autoconfigure/jdbc/DataSourceConfiguration$Hikari.class]: Bean instantiation via factory method failed; nested exception is org.springframework.beans.BeanInstantiationException: Failed to instantiate [com.zaxxer.hikari.HikariDataSource]: Factory method 'dataSource' threw exception; nested exception is java.lang.IllegalStateException: Cannot load driver class: org.h2.Driver  
	at org.springframework.beans.factory.support.ConstructorResolver.createArgumentArray(ConstructorResolver.java:800) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.ConstructorResolver.instantiateUsingFactoryMethod(ConstructorResolver.java:541) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.instantiateUsingFactoryMethod(AbstractAutowireCapableBeanFactory.java:1352) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBeanInstance(AbstractAutowireCapableBeanFactory.java:1195) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:582) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:542) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:335) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:234) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:333) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:208) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:322) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:208) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.context.support.AbstractApplicationContext.getBean(AbstractApplicationContext.java:1154) ~[spring-context-5.3.16.jar:5.3.16]
	at org.springframework.context.support.AbstractApplicationContext.finishBeanFactoryInitialization(AbstractApplicationContext.java:908) ~[spring-context-5.3.16.jar:5.3.16]
	at org.springframework.context.support.AbstractApplicationContext.refresh(AbstractApplicationContext.java:583) ~[spring-context-5.3.16.jar:5.3.16]
	at org.springframework.boot.web.servlet.context.ServletWebServerApplicationContext.refresh(ServletWebServerApplicationContext.java:145) ~[spring-boot-2.6.4.jar:2.6.4]
	at org.springframework.boot.SpringApplication.refresh(SpringApplication.java:740) ~[spring-boot-2.6.4.jar:2.6.4]
	at org.springframework.boot.SpringApplication.refreshContext(SpringApplication.java:415) ~[spring-boot-2.6.4.jar:2.6.4]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:303) ~[spring-boot-2.6.4.jar:2.6.4]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1312) ~[spring-boot-2.6.4.jar:2.6.4]
	at org.springframework.boot.SpringApplication.run(SpringApplication.java:1301) ~[spring-boot-2.6.4.jar:2.6.4]
	at com.Springboot_Microservice.Springboot_Microservice.SpringbootMicroserviceApplication.main(SpringbootMicroserviceApplication.java:10) ~[classes/:na]
Caused by: org.springframework.beans.factory.BeanCreationException: Error creating bean with name 'dataSource' defined in class path resource [org/springframework/boot/autoconfigure/jdbc/DataSourceConfiguration$Hikari.class]: Bean instantiation via factory method failed; nested exception is org.springframework.beans.BeanInstantiationException: Failed to instantiate [com.zaxxer.hikari.HikariDataSource]: Factory method 'dataSource' threw exception; nested exception is java.lang.IllegalStateException: Cannot load driver class: org.h2.Driver  
	at org.springframework.beans.factory.support.ConstructorResolver.instantiate(ConstructorResolver.java:658) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.ConstructorResolver.instantiateUsingFactoryMethod(ConstructorResolver.java:638) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.instantiateUsingFactoryMethod(AbstractAutowireCapableBeanFactory.java:1352) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBeanInstance(AbstractAutowireCapableBeanFactory.java:1195) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.doCreateBean(AbstractAutowireCapableBeanFactory.java:582) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractAutowireCapableBeanFactory.createBean(AbstractAutowireCapableBeanFactory.java:542) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractBeanFactory.lambda$doGetBean$0(AbstractBeanFactory.java:335) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.DefaultSingletonBeanRegistry.getSingleton(DefaultSingletonBeanRegistry.java:234) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractBeanFactory.doGetBean(AbstractBeanFactory.java:333) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.AbstractBeanFactory.getBean(AbstractBeanFactory.java:208) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.config.DependencyDescriptor.resolveCandidate(DependencyDescriptor.java:276) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.DefaultListableBeanFactory.doResolveDependency(DefaultListableBeanFactory.java:1389) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.DefaultListableBeanFactory.resolveDependency(DefaultListableBeanFactory.java:1309) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.ConstructorResolver.resolveAutowiredArgument(ConstructorResolver.java:887) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.ConstructorResolver.createArgumentArray(ConstructorResolver.java:791) ~[spring-beans-5.3.16.jar:5.3.16]
	... 21 common frames omitted
Caused by: org.springframework.beans.BeanInstantiationException: Failed to instantiate [com.zaxxer.hikari.HikariDataSource]: Factory method 'dataSource' threw exception; nested exception is java.lang.IllegalStateException: Cannot load driver class: org.h2.Driver  
	at org.springframework.beans.factory.support.SimpleInstantiationStrategy.instantiate(SimpleInstantiationStrategy.java:185) ~[spring-beans-5.3.16.jar:5.3.16]
	at org.springframework.beans.factory.support.ConstructorResolver.instantiate(ConstructorResolver.java:653) ~[spring-beans-5.3.16.jar:5.3.16]
	... 35 common frames omitted
Caused by: java.lang.IllegalStateException: Cannot load driver class: org.h2.Driver  
	at org.springframework.util.Assert.state(Assert.java:97) ~[spring-core-5.3.16.jar:5.3.16]
	at org.springframework.boot.autoconfigure.jdbc.DataSourceProperties.determineDriverClassName(DataSourceProperties.java:241) ~[spring-boot-autoconfigure-2.6.4.jar:2.6.4]
	at org.springframework.boot.autoconfigure.jdbc.DataSourceProperties.initializeDataSourceBuilder(DataSourceProperties.java:193) ~[spring-boot-autoconfigure-2.6.4.jar:2.6.4]
	at org.springframework.boot.autoconfigure.jdbc.DataSourceConfiguration.createDataSource(DataSourceConfiguration.java:48) ~[spring-boot-autoconfigure-2.6.4.jar:2.6.4]
	at org.springframework.boot.autoconfigure.jdbc.DataSourceConfiguration$Hikari.dataSource(DataSourceConfiguration.java:90) ~[spring-boot-autoconfigure-2.6.4.jar:2.6.4]
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[na:na]
	at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62) ~[na:na]
	at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[na:na]
	at java.base/java.lang.reflect.Method.invoke(Method.java:566) ~[na:na]
	at org.springframework.beans.factory.support.SimpleInstantiationStrategy.instantiate(SimpleInstantiationStrategy.java:154) ~[spring-beans-5.3.16.jar:5.3.16]
	... 36 common frames omitted

Disconnected from the target VM, address: '127.0.0.1:60140', transport: 'socket'

Process finished with exit code 1