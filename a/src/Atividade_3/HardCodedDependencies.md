```java
public class HardCodedDependencies {
    public static void main(String[] args) {
        Report report = new Report();
        report.generatePDFReport();
    }
}

class Report {
    public void generatePDFReport() {
        System.out.println("Generating PDF Report...");
    }
}
```

1-  A classe HardCodedDependencies esta sendo instanciada sem chamar o método