# java_practice
# Java Practice Repository

This repository contains basic Java programs for beginners to practice fundamental concepts.

---

## 🔢 1. Simple Integer Sum (Hardcoded)

```java
public class SumExample {
    public static void main(String[] args) {
        int a = 4;
        int b = 5;
        int sum = a + b;

        System.out.println("Sum of a and b is: " + sum);
    }
}
---java
##🔢 2. Sum Using Scanner Input

import java.util.Scanner;

public class ScannerSum {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int a = sc.nextInt();

        System.out.print("Enter second number: ");
        int b = sc.nextInt();

        int sum = a + b;
        System.out.println("Total Sum: " + sum);
    }
}
🧩 3. Pattern Printing Using Nested Loops
This program prints the following pattern:

1
11
111
1111
11111

public class PatternPrinter {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print("1");
            }
            System.out.println();
        }
    }
}
📂 Folder Structure
Copy
Edit
java_practice/
├── SumExample.java
├── ScannerSum.java
├── PatternPrinter.java
└── README.md
