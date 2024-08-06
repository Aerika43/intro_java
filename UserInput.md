# UserInput
#### The Scanner class is used to get user input, and it is found in the java.util package.
#### This "Scanner sc = Scanner(System.in);" is to be written in the main class
- you may change the object ie. sc
- you may write whatever you want to.
#### This "import java.util.Scanner;" is to be written above the main class.
---
## Syntax
```java
import java.util.Scanner;
public class main{
    public static void main(String[] args) {
  Scanner sc = Scanner(System.in);
    }
}
```
## Input Types

![alt text](userinput.png)

## Example:
```java
import java.util.Scanner;

class Main {
  public static void main(String[] args) {
   Scanner sc = new Scanner(System.in);
    System.out.println("String (with spacing): ");
    String s = sc.nextLine();

    System.out.println("String (no spacing): ");
    String s1 = sc.next();
    
    System.out.println("Integer: ")
    int i = sc.nextInt();

    System.out.println("Float: ")
    float f = sc.nextFloat();

    System.out.println("Double: ")
    double d = sc.nextDouble();

    System.out.println("Boolean: ")
    boolean b = sc.nextBoolean();

    System.out.println("Long: ")
    long l = sc.nectLong();
 
  }
}
```
