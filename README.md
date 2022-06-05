# SpringBoot-annotations-cheat-sheet

|                        | Annotations                  | Description                                                  |
| ---------------------- | ---------------------------- | ------------------------------------------------------------ |
| **Main Class**         | @SpringBootApplication       | Spring Boot auto configuration                               |
|                        |                              |                                                              |
| **REST Endpoint**      | @RestController              | Class with REST endpoints                                    |
|                        | @RequestMapping              | REST endpoint method                                         |
|                        | @PathVariable                | URI path parameter                                           |
|                        | @RequestBody                 | HTTP request body                                            |
|                        |                              |                                                              |
| **Periodic Tasks**     | @Scheduled                   | Method to run periodically                                   |
|                        | @EnableScheduling            | Enable Spring's task scheduling                              |
|                        |                              |                                                              |
| **Beans**              | @Configuration               | A class containing Spring beans                              |
|                        | @Bean                        | Objects to be used by Spring loC for <br />dependency injection |
|                        |                              |                                                              |
| **Spring** **Managed** | @Component                   | A candidate for dependency injection                         |
| **Components**         | @Service                     | Like @Component                                              |
|                        | @Repository                  | Like @Component, for data base access                        |
|                        |                              |                                                              |
| **Persistence**        | @Entity                      | A class which can be stored in the data base<br /> via ORM   |
|                        | @Id                          | Primary key                                                  |
|                        | @GeneratedValue              | Generation strategy of primary key                           |
|                        | @EnableipaRepositories       | Triggers the search for classes with<br /> @Repository annotation |
|                        | @EnableTransactionManagement | Enable Spring's DB transaction management<br /> through @Beans objects |
|                        |                              |                                                              |
| **Miscellaneous**      | @Autowired                   | Force dependency injection                                   |
|                        | @ConfigurationProperties     | Import settings from properties file                         |
|                        |                              |                                                              |
| **Testing**            | @SpringBootTest              | Spring integration test                                      |
|                        | @AutoConfigureMockMvc        | Configure MockMvc object to test HTTP                        |



