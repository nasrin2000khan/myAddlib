**Basic methods**

| Method                   | Description                        | Example           | Output (e.g.) |
| ------------------------ | ---------------------------------- | ----------------- | ------------- |
| `add(int a, int b)`      | Adds two numbers                   | `add(5, 3)`       | `8`           |
| `subtract(int a, int b)` | Subtracts second number from first | `subtract(10, 4)` | `6`           |
| `multiply(int a, int b)` | Multiplies two numbers             | `multiply(6, 7)`  | `42`          |
| `divide(int a, int b)`   | Divides first number by second     | `divide(20, 5)`   | `4`           |
| `modulus(int a, int b)`  | Returns remainder after division   | `modulus(10, 3)`  | `1`           |


Advanced Methods

| Method                     | Description                    | Example           | Output (e.g.) |
| -------------------------- | ------------------------------ | ----------------- | ------------- |
| `square(int a)`            | Returns square of a number     | `square(6)`       | `36`          |
| `cube(int a)`              | Returns cube of a number       | `cube(4)`         | `64`          |
| `power(int base, int exp)` | Raises number to power         | `power(2, 5)`     | `32`          |
| `average(int a, int b)`    | Returns average of two numbers | `average(10, 20)` | `15`          |
| `max(int a, int b)`        | Returns maximum value          | `max(9, 15)`      | `15`          |



🧩 Example Implementation (Test Code)


public class TestMath {

    public static int add(int a, int b) {
        return a + b;
    }

    public static int subtract(int a, int b) {
        return a - b;
    }

    public static int multiply(int a, int b) {
        return a * b;
    }

    public static int divide(int a, int b) {
        return a / b;
    }

    public static int modulus(int a, int b) {
        return a % b;
    }

    public static int square(int a) {
        return a * a;
    }

    public static int cube(int a) {
        return a * a * a;
    }

    public static int power(int base, int exp) {
        return (int) Math.pow(base, exp);
    }

    public static int average(int a, int b) {
        return (a + b) / 2;
    }

    public static int max(int a, int b) {
        return Math.max(a, b);
    }
}


🧪 Sample Usage


System.out.println(add(5,3));        // 8
System.out.println(subtract(10,4));  // 6
System.out.println(multiply(6,7));   // 42
System.out.println(divide(20,5));    // 4
System.out.println(square(6));       // 36
