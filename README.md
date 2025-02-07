#### Hey, I'm Vidhura Neethika  

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
        "Cloud Computing"
    };

    private static final String[] TECH_STACK = {
        "Java", "Spring Boot", "Hibernate", "PHP", "Laravel",
        "Java Script", "Type Script", "Node.js", 
        "React", "Express.js", "Next.js", "Framer Motion", "React Native",
        "MySQL", "PostgreSQL", "Firebase",
        "AWS", "Docker"
    };

    public static void main(String[] args) {
        System.out.println("Hey!");
        System.out.println("I am " + NAME + ", a passionate " + POSITION + " Based in " + COUNTRY + ".");
        System.out.println("My interests include:");
        for (String interest : INTERESTS) {
            System.out.println(" - " + interest);
        }
        System.out.println("My tech stack:");
        for (String item : TECH_STACK) {
            System.out.println(" - " + item);
        }
        System.out.println("Check out my portfolio: " + PORTFOLIO);
        System.out.println("Let's connect and build something amazing!");
    }
}

```

