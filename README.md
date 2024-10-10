![image](https://github.com/user-attachments/assets/712bc453-e4aa-4fb9-b5f8-384d397ee50f)

# Java
Java Tutorial Notes

**Java: A Versatile Programming Language**

Java is a high-level, object-oriented programming language known for its platform independence, reliability, and security. It was originally designed by Sun Microsystems (now owned by Oracle) in the early 1990s.

**Key Features of Java:**

* **Platform Independence:** Java's "Write Once, Run Anywhere" (WORA) principle means that compiled Java code can run on any system with a Java Virtual Machine (JVM) installed, regardless of the underlying operating system or hardware architecture.
* **Object-Oriented Programming (OOP):** Java is built around the concept of objects, which encapsulate data and behavior. This makes it easier to model real-world problems and create modular, reusable code.
* **Garbage Collection:** Java's automatic memory management system, known as garbage collection, frees programmers from the burden of manual memory allocation and deallocation, reducing the risk of memory leaks.
* **Strong Typing:** Java is a strongly typed language, which means that variables must be declared with a specific data type, ensuring type safety and preventing common programming errors.
* **Security:** Java has built-in security features, such as bytecode verification and sandboxing, to protect against malicious code and security vulnerabilities.
* **Large Standard Library:** Java comes with a rich standard library that provides a wide range of classes and methods for common programming tasks, such as input/output, networking, and data structures.

**Common Uses of Java:**

* **Enterprise Applications:** Java is widely used for developing large-scale enterprise applications, including web applications, database systems, and server-side software.
* **Android App Development:** Java is the primary programming language for developing Android apps, which power billions of devices worldwide.
* **Web Development:** Java can be used to create web applications using frameworks like Spring and Struts.
* **Scientific Computing:** Java is used in scientific computing and research due to its numerical precision and libraries like Apache Commons Math.
* **Big Data:** Java is a popular choice for big data processing and analysis, with frameworks like Hadoop and Spark.

## History of Java

The language developed for this project was initially called Oak, but it was later renamed Java. The name was inspired by a coffee shop near Sun's offices.

### Key Milestones in Java's History:

* **1995:** Java 1.0 was released, marking its official debut.
* **1996:** Java became the official language for developing applications for Sun's Solaris operating system.
* **1997:** Java 1.1 was released with significant improvements, including inner classes and JDBC (Java Database Connectivity).
* **1998:** Java 2 (also known as J2SE, J2EE, and J2ME) was introduced, dividing Java into three editions for different platforms.
* **2004:** Java 5 (also known as J2SE 5.0) was released with several new features, including generics, autoboxing/unboxing, and enhanced for loops.
* **2014:** Java 8 was released with major updates, including lambda expressions, streams, and a default method for interfaces.
* **2017:** Java 9 was released with a modular system, known as Project Jigsaw.
* **2018:** Java 10 was released with a new garbage collector and minor language enhancements.
* **2021:** Java 17 was released as a long-term support (LTS) release, providing long-term support and stability.

Java has continued to evolve and adapt over the years, remaining a popular and versatile programming language used in various domains, from enterprise applications to mobile app development.

**Simple "Hello, World!" program in Java:**

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

### Explanation:

1. **`public class HelloWorld`:** This line declares a public class named `HelloWorld`. Classes are the fundamental building blocks of Java programs.
2. **`public static void main(String[] args)`:** This is the main method of the program. It's the entry point where execution begins.
   - `public`: This keyword makes the method accessible from outside the class.
   - `static`: This keyword means the method belongs to the class itself, not to individual instances of the class.
   - `void`: This indicates that the method doesn't return any value.
   - `main(String[] args)`: This is the name of the method and takes an array of strings as input arguments.
3. **`System.out.println("Hello, World!");`:** This line prints the message "Hello, World!" to the console.
   - `System.out`: This refers to the standard output stream (usually the console).
   - `println()`: This method prints the given string to the console and adds a newline character.

### To run this program:

1. **Save the code:** Save the code as a `.java` file (e.g., `HelloWorld.java`).
2. **Compile the code:** Use the Java compiler (javac) to compile the `.java` file into a `.class` file (e.g., `javac HelloWorld.java`).
3. **Run the program:** Use the Java Runtime Environment (JRE) to run the `.class` file (e.g., `java HelloWorld`).

This will output "Hello, World!" to the console.

**Java Escape Sequences**

Escape sequences are special character combinations used to represent characters that are difficult to type directly or have special meanings in Java. They are preceded by a backslash (`\`) to indicate that the following characters should be interpreted as an escape sequence.

Here are some common Java escape sequences:

| Escape Sequence | Character Represented |
|---|---|
| `\n` | Newline |
| `\t` | Tab |
| `\r` | Carriage return |
| `" ` | Double quote |
| `\'` | Single quote |
| `\\` | Backslash |
| `\b` | Backspace |
| `\f` | Form feed |

**Examples:**

```java
String text = "This is a\nmultiline string.";
System.out.println(text);

String path = "C:\\Users\\John\\Documents\\file.txt";
System.out.println(path);
```

In the first example, the `\n` escape sequence is used to insert a newline character, making the string multiline. In the second example, the `\\` escape sequence is used to represent a literal backslash character in the file path.

**Additional Notes:**

* You can also use Unicode escape sequences to represent characters that are not easily represented using ASCII. For example, `\u0020` represents a space character.
* When using escape sequences within strings, it's often a good practice to use double quotes to avoid conflicts with single quotes. For example, `"\'"` represents a single quote character.

By understanding and using escape sequences, you can create more complex and accurate strings in your Java programs.
