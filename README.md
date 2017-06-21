# features

## dependencies check 
* gtc
* gy
* jar


## manifest
* token
* permission


## manifestPlaceholders


## repositories

## proguard 

# usage 

1. Build script snippet for use in all Gradle versions:
```groovy
buildscript {
  repositories {
    maven {
      url "https://plugins.gradle.org/m2/"
    }
  }
  dependencies {
    classpath "com.getui:gy-check-plugin:latest"
  }
}

apply plugin: "getui.gy-check"
```

2. Build script snippet for new, incubating, plugin mechanism introduced in Gradle 2.1:

```groovy
plugins {
  id "getui.gy-check" version "latest"
}

```

3.  根项目下 `gradle gycheck` 即可看到检查结果
