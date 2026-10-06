```java
import java.util.Map;

public class AboutMe {
    public static void main(String[] args) {
        Developer narah = Developer.builder()
            .name("Narah Souza")
            .location("Brasília, DF - Brazil 🇧🇷")
            .education("Systems Analysis & Dev (Grad) | Project Management (Postgrad)")
            .currentFocus("Java Backend & Systems Architecture")
            .contacts(Map.of(
                "linkedin", "linkedin.com/in/narahsouza",
                "email", "narahsouza.dev@gmail.com"
            ))
            .build();

        narah.printProfile();
    }
}
```
