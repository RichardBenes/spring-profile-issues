# Issues with profile specification

## Working one

```PowerShell
Clear-Host; mvn clean install; mvn spring-boot:run -'Dspring-boot.run.jvmArguments="-Dspring.profiles.active=local"' --projects app
```

## Non-working one

```PowerShell
Clear-Host; mvn clean install; mvn spring-boot:run -'Dspring-boot.run.profiles=local' --projects app
```

