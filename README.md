#### Hey,I'm Vidhura Neethika  

```java

public class AboutMe {
    
    private static final String NAME = "Vidhura Neethika Udayananda";
    private static final String POSITION = "Software Engineer";
    private static final String COUNTRY = "Sri Lanka";
    private static final String PORTFOLIO = "vidhuraneethika.vercel.app";
    
    private static final String[] INTERESTS = {
        "Full Stack Development",
        "Mobile App Development",
        "DevOps",
        "UI/UX Design",
    };

    private static final String[] SKILLS = {
        "Spring Boot", "Node.js", "Laravel", "MySQL", "PHP", "Tailwind CSS",
        "React", "Express.js", "Amazon Web Services", "PostgreSQL", "Java", 
        "Docker", "React Native", "Next.js", "Firebase", "Hibernate", "Framer Motion"
    };

    public static void main(String[] args) {
        System.out.println("Hey!");
        System.out.println("I am " + NAME + ", a passionate " + POSITION + " from " + COUNTRY + ".");
        System.out.println("My interests include:");
        for (String interest : INTERESTS) {
            System.out.println(" - " + interest);
        }
        System.out.println("Check out my portfolio: " + PORTFOLIO);
        System.out.println("Let's connect and build something amazing!");
    }
}

