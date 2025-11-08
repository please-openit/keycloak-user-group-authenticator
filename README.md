# Conditional user group authenticator

The implementation of : https://github.com/keycloak/keycloak/issues/36788

## Build

This project uses Maven, needs at least JDK 2x1 (openjdk).

```
mvn clean install
```

## Deploy

Copy generated jar file from "deployments" directory to "providers" directory in Keycloak
