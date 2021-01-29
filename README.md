# Repos

Protect your users accounts<br>
[More info](https://www.spigotmc.org/resources/gsa-locklogin.75156/)

## How to?
### pom (maven)
```xml
<repositories>
  <repository>
    <id>Repos-master</id>
    <url>https://github.com/KarmaConfigs/Repos/raw/master/</url>
  </repository>
</repositories>

<dependencies>
  <dependency>
    <groupId>ml.karmaconfigs</groupId>
    <artifactId>LockLogin</artifactId>
    <version>1.0.5.2</version>
    <scope>provided</scope>
  </dependency>
</dependencies>
```

### gradle
```gradle
repositories {
    maven { url "https://github.com/KarmaConfigs/Repos/raw/master/" }
}

dependencies {
    compile "ml.karmaconfigs:LockLogin:1.0.5.2"
}
