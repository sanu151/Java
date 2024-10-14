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

#### Key Milestones in Java's History:

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

### Simple "Hello, World!" program in Java:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

#### Explanation:

1. **`public class HelloWorld`:** This line declares a public class named `HelloWorld`. Classes are the fundamental building blocks of Java programs.
2. **`public static void main(String[] args)`:** This is the main method of the program. It's the entry point where execution begins.
   - `public`: This keyword makes the method accessible from outside the class.
   - `static`: This keyword means the method belongs to the class itself, not to individual instances of the class.
   - `void`: This indicates that the method doesn't return any value.
   - `main(String[] args)`: This is the name of the method and takes an array of strings as input arguments.
3. **`System.out.println("Hello, World!");`:** This line prints the message "Hello, World!" to the console.
   - `System.out`: This refers to the standard output stream (usually the console).
   - `println()`: This method prints the given string to the console and adds a newline character.

#### To run this program:

1. **Save the code:** Save the code as a `.java` file (e.g., `HelloWorld.java`).
2. **Compile the code:** Use the Java compiler (javac) to compile the `.java` file into a `.class` file (e.g., `javac HelloWorld.java`).
3. **Run the program:** Use the Java Runtime Environment (JRE) to run the `.class` file (e.g., `java HelloWorld`).

This will output "Hello, World!" to the console.

## Java Escape Sequences

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

## Java Comments

Comments in Java are used to explain the code, make it more readable, and provide documentation. They are ignored by the compiler, so they have no effect on the program's execution.

There are three types of comments in Java:

1. **Single-line comments:**
   - Start with `//` and end at the end of the line.
   - Example:
     ```java
     // This is a single-line comment
     ```

2. **Multi-line comments:**
   - Start with `/*` and end with `*/`.
   - Can span multiple lines.
   - Example:
     ```java
     /* This is a
     multi-line comment */
     ```

3. **Javadoc comments:**
   - Start with `/**` and end with `*/`.
   - Used to generate API documentation.
   - Can contain HTML tags.
   - Example:
     ```java
     /**
      * This is a Javadoc comment.
      *
      * @param name The name to be printed.
      */
     public void printName(String name) {
         System.out.println("Hello, " + name + "!");
     }
     ```

**Best Practices for Comments:**

* **Use comments to explain non-obvious code.** Avoid commenting on trivial or self-explanatory code.
* **Keep comments concise and to the point.** Avoid writing long, rambling comments.
* **Update comments whenever you modify the code.** Ensure that comments accurately reflect the current state of the code.
* **Use consistent formatting for comments.** This makes the code easier to read and understand.
* **Use Javadoc comments to document public methods and classes.** This helps others understand how to use your code.

By following these guidelines, you can write well-documented and maintainable Java code.

## Phases of a Java Program

A Java program typically goes through several phases from creation to execution. Let's break down these phases with detailed steps and a flowchart:

### 1. **Source Code Writing**
* **Step 1:** Create a new text file using a text editor or IDE.
* **Step 2:** Write your Java code in the file, following Java's syntax and semantics.
* **Example:**
  ```java
  public class HelloWorld {
      public static void main(String[] args) {
          System.out.println("Hello, World!");
      }
  }
  ```

### 2. **Compilation**
* **Step 1:** Save the file with a `.java` extension (e.g., `HelloWorld.java`).
* **Step 2:** Use the Java compiler (javac) to compile the source code.
* **Command:** `javac HelloWorld.java`
* **Result:** The compiler creates a `.class` file (e.g., `HelloWorld.class`) containing the bytecode.

### 3. **Class Loading**
* **Step 1:** The Java Virtual Machine (JVM) loads the `.class` file into memory.

### 4. **Bytecode Verification**
* **Step 1:** The JVM verifies the bytecode to ensure it's safe and adheres to Java's rules.
* **Step 2:** If the verification fails, the JVM throws an error and the program terminates.

### 5. **Linking**
* **Step 1:** The JVM links the loaded class with other necessary classes and libraries.
* **Step 2:** This involves resolving references to external classes and methods.

### 6. **Initialization**
* **Step 1:** The JVM initializes static variables and executes static blocks of code.

### 7. **Execution**
* **Step 1:** The JVM executes the bytecode instructions, carrying out the program's logic.
* **Step 2:** This involves creating objects, calling methods, and performing calculations.

### 8. **Garbage Collection**
* **Step 1:** The JVM automatically manages memory allocation and deallocation.
* **Step 2:** When objects are no longer needed, they are reclaimed by the garbage collector.

### Flowchart

![image](https://github.com/user-attachments/assets/79495bf7-31bc-4bea-8dab-812660c1d1a1)



**Note:** These phases are repeated for each class in a Java program. The JVM manages the entire process seamlessly, providing a platform-independent and secure execution environment.
