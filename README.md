<h3 align="center">📄 Favorite Languages:</h3>
<p align="center">
<a target="_blank"><img alt="SQL" src="https://img.shields.io/badge/-JAVA-%2312100E.svg?logo=microsoft-sql-server&logoColor=red&style=for-the-badge"/></a> 
<a target="_blank"><img alt="Python" src="https://img.shields.io/badge/Python-%2312100E.svg?logo=python&style=for-the-badge&logoColor=yellow"/></a> 

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
