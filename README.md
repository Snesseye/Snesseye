public class Snesseye extends GitHubUser {

  public Snesseye() {
    super("Snesseye", "Belgium");

    this.addLanguage("Java", "Python");
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
