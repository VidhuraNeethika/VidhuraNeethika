#### Hello, I'm Vidhura Neethika Udayananda  

##### About Me  
```java

public class VidhuraNeethika {
    
    private static final String NAME = "Vidhura Neethika Udayananda";
    private static final String POSITION = "Software Engineer";
    private static final String LOCATION = "Sri Lanka";
    
    private static final String[] INTERESTS = {
        "Full Stack Development",
        "DevOps",
        "Cloud Computing",
        "Machine Learning",
        "Open Source Contributions"
    };

    private static final String[] SKILLS = {
        "Spring Boot", "Node.js", "Laravel", "MySQL", "PHP", "Tailwind CSS",
        "React", "Express.js", "Amazon Web Services", "PostgreSQL", "Java", 
        "Docker", "React Native", "Next.js", "Firebase", "Hibernate", "Framer Motion"
    };

    public static void main(String[] args) {
        System.out.println("Hey!");
        System.out.println("I am " + NAME + ", a passionate " + POSITION + ".");
        System.out.println("My interests include:");
        for (String interest : INTERESTS) {
            System.out.println(" - " + interest);
        }
        System.out.println("Let's connect and build something amazing!");
    }
}
