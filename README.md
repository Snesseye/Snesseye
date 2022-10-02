<a href="https://twitter.com/OofJoa" target="blank"><img src="https://img.shields.io/twitter/follow/iFlyinqMC?logo=twitter&style=for-the-badge" alt="Snesseye"/></a> 
<img src="https://visitor-badge.glitch.me/badge?page_id=snesseye" alt="Snesseye visit count"/>

```java
public class Snesseye extends GitHubUser {

  public Snesseye() {
    super("Snesseye", "Belgium");

    this.addLanguage("Java", "C#", "Python");
  }
}

public abstract class GitHubUser {

  private final String name;
  private final String country;

  private ArrayList<String> languages = new ArrayList<>();

  public GitHubUser(String name, String country) {
      this.name = name;
      this.country = country;
  }

  public void addLanguage(String... languages) {
    languages.addAll(languages);
  }
  
}
```

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=Snesseye&count_private=true&show_icons=true&theme=dark&hide_border=false" alt="github stats">
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/wakatime?username=@Snesseye&theme=dark&show_iconsk&count_private=true" alt="wakatime stats" height=195>
    </td>
  </tr>
</table>
