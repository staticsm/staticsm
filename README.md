```java
public class Sy extends Person {
    private String name;
    private int age;
    private List<String> work;
    private List<String> education;
    private List<String> hobbies;

    public Sy() {
        this.name = "Static";
        this.age = 17;
        this.work = Arrays.asList("Comp Sci Student");
        this.hobbies = Arrays.asList("Gaming", "Engineering", "Homelabbing");
    }

    public String currentLocation() {
        return "CT, South Africa";
    }

    public Map<String, List<String>> currently() {
        return Map.of(
            "studying", Arrays.asList("Computer Science"),
            "tinkering", Arrays.asList("Docker Swarm", "Kubernetes")
        );
    }
}
```
