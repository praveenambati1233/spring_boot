
@SpringBootApplication annotation enables  three features,

> @EnableAutoConfiguration  -- Start up default configurations
@ComponentScan - enable @Component scan on the package where the application is located. Performs class path scan.
@Configuration - allow to register extra beans in the context or import additional configuration classes. **Starts Spring application context.**
- Provides embedded Tomcat server.


Application properties : https://docs.spring.io/spring-boot/docs/current/reference/html/appendix-application-properties.html


|  ID  |  Annotation  |  Desc  |
| ------------ | ------------ | ------------ |
|  1  | @RequestMapping  |   |
|  2  | @WebAppConfiguration  |  For MVC configuration |
| 3   |  @SpringBootApplication  |   |
|  4  |  @EntityScan(basePackages="room.springboot.model")  |  JPA entities or Hibernate entities |
| 5   |  @EnableJpaRepositories(basePackages="room.springboot.*")  |  JPA repositories  |
|  6 |  @ComponentScan("room.springboot.controller")   |  Any component classes you have  |
|  7 |  @EnableAutoConfiguration  |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |
|   |   |   |




































Maven: 

artifactId - project name
groupId - package name that uniquely identifies the name space for the project.
version - version of the component
