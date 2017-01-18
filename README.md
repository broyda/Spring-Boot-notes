# Spring-Boot-notes
```
Actuators for monitoring
pom.xml updates 
can change the port # for monitoring

Spring initializr

### Important annotations
@Service
@RequestController
@RequestMapping("ser/v1")
@RequestBody
@PathVariable

Profiles
@ConfigurationProperties - third party code

JPA
----
@Entity
@Id
@ManyToOne



Tests
------
@RunWith
@SpringApplicationConfiguration
@WebIntegrationtest

extends CrudRepository<Entity name, String>
findAll() - returns an iterable
findAll().forEach(someList::add); //lambda expression

save(Entity)  - upsert
```
