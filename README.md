## Hello! I'm Santino, this is my personal profile with info about me and my projects.




```java
public class AboutMe {

  public static void main(String[] args) {

    final String ME = "Santino Colombo Ruscio 🙋‍♂️";

    final String[] LANGUAGES = {
      "Java", 
      "Javascript", 
      "HTML", 
      "CSS", 
      "Python", 
      "SQL"
    };

    final String[] INTERESTS = {
      "Gaming 🎮", 
      "Programming 💻", 
      "Music 🎵"
    };

    final String CONTACT = "www.linkedin.com/in/santino-colombo-ruscio";

    System.out.println("Hello! I'm " + ME);
    System.out.println("Languages I use:");
    for(String lang : LANGUAGES) {
      System.out.println("- " + lang);
    }
    System.out.println("My interests include:");
    for(String interest : INTERESTS) {
      System.out.println("- " + interest);
    }
    System.out.println("Connect with me on LinkedIn: " + CONTACT);
  }
}
