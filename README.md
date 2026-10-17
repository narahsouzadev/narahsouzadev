## 👩‍💻 About
```java
import java.util.Map;

public class AboutMe {
    public static void main(String[] args) {
        Developer narah = Developer.builder()
            .name("Narah Souza")
            .location("Brasília, Brazil")
            .education("Bachelor's Degree in Software Engineering 🎓 In progress)")
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
## 📊 Activity
[![GitHub Stats](https://github-stats-extended.vercel.app/api/top-langs?username=narahsouzadev&layout=compact&langs_count=6&theme=transparent)](https://github-stats-extended.vercel.app/api/top-langs?username=narahsouzadev&layout=compact&langs_count=6&theme=transparent)
