#### PREPAIR ENVIORMENT
- install gradle binary-only 7.6.1 (environment variable)
- install java home jdk 17.0.5 (environment variable)
- install eclipse java EE (Ide)

#### NEW GRADLE API PROJECT
eclipse>newProject>gradleProject
rm library.java
rm java.test
- build.gradle
  - id 'application' (necessary)
  - id 'java' (not necessary)
  - id 'eclipse' (not necessary)

access web: mvnRepository > spring boot starter web 3.0.4
 add in project

btn direito no projeto/show in local terminal
c:.../ProjectName/lib> gradle build
dir

- gradle>refreshGradleProject

- create class in src/main/java > package > Aplication.java && TestController.java

- run api: Application.java > Run as > java Application

- GET localhost:8080/test

- src/main/resources/Application.properties

```java
@Bean("name")
@Qualifier("name")
```

POSTMAN
- Params > url
- Headers > settings
- Body > Json
