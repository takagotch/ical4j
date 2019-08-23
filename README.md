### ical4j
---
https://github.com/ical4j/ical4j

```java
// src/test/java/net/fortuna/ical4j/transform/frc5545/CreatedPropertyRuleTest.java

public static CreatedPropertyRuleTest {

  @Test
  public void shouldSetUtcToBrokenCreatedDate() throws ParseException {
    Created created = new Created("20161026T130842");
    RuleManager.applyTo(created);
  }
}
```

```sh
./gradlew clean test
./gradlew clean test release -Prelease.forceVersion=2.0.0
RELEASE_VERSION=2.0.0 ./gradlew uploadArchives uploadDist
```

```
```


