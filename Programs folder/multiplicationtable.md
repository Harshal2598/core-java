```java
package programs;

// Class to print the multiplication table of a given number
public class multiplicationtable {

    // Instance variable to store the number for which table will be printed
    public int a;

    // Constructor to initialize the value of 'a'
    multiplicationtable(int a) {
        this.a = a;
    }

    // Method to print the multiplication table of the number passed as argument
    public void printtable(int a) {

        // Loop from 0 to 9 (total 10 iterations)
        for (int i = 0; i < 10; i++) {
            // Prints: a X i = result
            System.out.println(a + " X " + i + " = " + (a * i));
        }
    }

    public static void main(String[] args) {
        // Creating object with value 5
        multiplicationtable table = new multiplicationtable(5);

        // Calling method to print table of 5
        table.printtable(5);
    }
}
```
