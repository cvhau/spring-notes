## Spring Boot Developer Tools and IntelliJ

Enable Spring Boot Developer Tools in IntelliJ

### 1. Add Spring Boot Developer Tools dependency

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-devtools</artifactId>
    <optional>true</optional>
</dependency>
```

You can go to [Spring Devtools Properties docs page](https://docs.spring.io/spring-boot/docs/current/reference/html/application-properties.html#appendix.application-properties.devtools) for further details of more config properties. 
### 2. Change IntelliJ IDEA settings

#### 2.1 Enable <i>Allow auto-make to start even if the developed application is currently running</i>
Under <i>Settings / Advanced Settings / Compiler</i> section.

![Image](./intellij-settings-auto-make.png)

#### 2.2 Enable <i>Build project automatically</i>
Under <i>Settings / Build, Execution, Deployment / Compiler</i> section.

If you don't want to check this option, you can press ```CTRL + F9``` each time you make changes in your project.

![Image](intellij-settings-auto-build-project.png)

### 3. Happy coding!

Finally, click on <i>Build / Build Project</i> and <i>Run / Run</i> to trigger build and run process in IntelliJ IDEA.
