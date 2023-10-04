1. query 
  - https://alejandromp.com/blog/experimenting-with-a-query-resolver-system/
  - https://github.com/alexito4/QueryResolverSystem

2. deployment
  - https://www.unison-lang.org/whats-new/unison-services-preview/
  - just as a quick waste of time, this seems interesting (cf nix gitlab vs docker, etc)

3. what i came here for
  - https://jenkov.com/tutorials/java-json/jackson-annotations.html
  - don't understand this now (it's 5 hours later, not now...)

  ```java
  InjectableValues inject = new InjectableValues.Std().addValue(String.class, "jenkov.com");
  PersonInject personInject = new ObjectMapper().reader(inject)
                        .forType(PersonInject.class)
                        .readValue(new File("data/person.json"));
  ``` 

4. Food stuffs
  - https://github.com/immutables/immutables
  - Also movie stars...

5. Am I a bad person?
  - https://stackoverflow.com/questions/47351968/how-to-make-githubs-immutables-work-in-intellij-gradle
