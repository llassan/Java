# Java

Java is a high-level, object-oriented, platform-independent programming language developed by Sun Microsystems in the mid-1990s (now owned by Oracle).

**1. JDK (Java Development Kit)**

It’s the full toolkit for developers.

Includes:

Compiler (javac) → converts your .java code into bytecode (.class files).

JRE (Java Runtime Environment) → so you can run what you write.

Tools like debuggers, profilers, and documentation generators.

Without JDK, you can’t develop Java apps — only run them.

**2. JRE (Java Runtime Environment)**

It’s the package to run Java applications.

Includes:

JVM (Java Virtual Machine) → executes bytecode.

Core Java libraries (collections, networking, IO, etc.).

End users who only need to run Java programs (not write them) just need JRE.

**3. JVM (Java Virtual Machine)**

The engine that makes Java platform-independent.

Takes compiled bytecode and translates it to machine code for the host OS.

Handles:

Memory management (via Garbage Collection).

Just-In-Time (JIT) compilation for faster execution.

Security checks (sandboxing for untrusted code).

***Flow of Execution***

You write Java code → MyApp.java.

JDK compiler (javac) compiles it → MyApp.class (bytecode).

JVM (inside JRE) loads and runs the bytecode on your OS.

Thanks to JVM, the same .class file runs on Windows, Mac, Linux, etc. without change.

👉 In short:

JDK = for developers (write + run).

JRE = for users (just run).

JVM = the core engine that makes Java portable.

**What is Statement?**
It is a complete command to be executed. It can consist of one or more expressions.

**What are Keywords?**
A keyword is a reserved word that has predefined meaning in Java Language.

**What is an Expression?**
An expression is a coding construct that evaluates to a single value.

## Data Types:

**_Primitive Data Types (8):_**

These are built-in, simple, and not objects. Stored directly in memory.


| Data Type | Size     | Default Value | Example              | Range                       |
|-----------|----------|---------------|----------------------|-----------------------------|
| byte      | 8-bit    | 0             | `byte a = 100;`      | -128 to 127                 |
| short     | 16-bit   | 0             | `short s = 1000;`    | -32,768 to 32,767           |
| int       | 32-bit   | 0             | `int x = 50000;`     | -2^31 to 2^31 - 1           |
| long      | 64-bit   | 0L            | `long l = 100000L;`  | -2^63 to 2^63 - 1           |
| float     | 32-bit   | 0.0f          | `float f = 5.75f;`   | ~7 decimal digits precision |
| double    | 64-bit   | 0.0d          | `double d = 19.99;`  | ~15 decimal digits precision|
| char      | 16-bit   | '\u0000'      | `char c = 'A';`      | 0 to 65,535 (Unicode)       |
| boolean   | 1 bit*   | false         | `boolean flag = true;` | true / false              |

> *Note: `boolean` size is JVM-dependent, but logically treated as 1 bit.

---

**_Non-Primitive (Reference) Data Types(5):_**

| Data Type | Example |
|-----------|---------|
| String    | `String name = "Java";` |
| Array     | `int[] arr = {1, 2, 3};` |
| Class     | `class Student { ... }` |
| Interface | `interface Shape { ... }` |
| Enum      | `enum Level { LOW, MEDIUM, HIGH }` |
