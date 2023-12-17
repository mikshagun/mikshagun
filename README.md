<h2 align="center">About Me</h2>

```java
import java.util.Map;

public class Mikvlw {
    private Object me;
}

public class Attributes extends Mikvlw {

    public Tuple<String, String, String> contact() {
        String discord = "m1kvlw";
        String telegram = "t.me/mikvlw";
        String email = "ishagunmv@yandex.com";

        return new Tuple<>(discord, telegram, email);
    }

    public Tuple<String[], Map<String, String[]>, String[], String[]> coding() {
        Map<String, String[]> libs = Map.of(
                "testing", new String[] {"testng, junit5, rest-assured, selenide, assertj, hamcrest", "allure"},
                "arch", new String[] {"lombok", "postgresql", "jackson", "javax", "mongodb", "rabbitmq", "slf4j"},
                "build", new String[] {"maven", "gradle"},
                "other", new String[] {"wiremock"}
        );

        String[] langs = {"java"};
        String[] specialities = {"qa automation engineer", "fullstack"};
        String[] environnement = {"intellij idea"};

        return new Tuple<>(libs, langs, specialities, environnement);
    }
}
```
<h2 align="center">Skills </h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=java,idea,jenkins,selenium,linux,docker,postgres,mongo,rabbitmq" />
  </a>
</p>
