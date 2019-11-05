# Getting Started

# Install
```sh
brew install gradle
```

# Gradle Init
```
gradle init --type java-application
```

# Add Dependencies
Update `build.gradle` to add springboot dependencies.

```shell script
id 'org.springframework.boot' version "2.1.1.RELEASE"
```

# Build
```
./gradlew build
```