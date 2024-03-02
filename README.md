# cloudevents-spring-amqp
CloudEvents Binding for Spring AMQP

![Maven Central Version](https://img.shields.io/maven-central/v/de.lyca.cloudevents/cloudevents-spring-amqp?link=https%3A%2F%2Fcentral.sonatype.com%2Fartifact%2Fde.lyca.cloudevents%2Fcloudevents-spring-amqp)
[![Coverage](.github/badges/jacoco.svg)](https://github.com/lyca/cloudevents-spring-amqp/actions/workflows/gradle.yml)
[![Branches](.github/badges/branches.svg)](https://github.com/lyca/cloudevents-spring-amqp/actions/workflows/gradle.yml)

**Gradle (Kotlin)**

```kotlin
implementation("de.lyca.cloudevents:cloudevents-spring-amqp:1.0.0")
```

**Gradle (Groovy)**

```groovy
implementation 'de.lyca.cloudevents:cloudevents-spring-amqp:1.0.0'
```

**Apache Maven**

```xml
<dependency>
    <groupId>de.lyca.cloudevents</groupId>
    <artifactId>cloudevents-spring-amqp</artifactId>
    <version>1.0.0</version>
</dependency>
```

**Usage**

```java
@Bean
public CloudEventMessageConverter cloudEventMessageConverter() {
    return new CloudEventMessageConverter();
}
```