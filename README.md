# Java

Java is a high-level, object-oriented, platform-independent programming language developed by Sun Microsystems in the mid-1990s (now owned by Oracle).
1. JDK (Java Development Kit)

It’s the full toolkit for developers.

Includes:

Compiler (javac) → converts your .java code into bytecode (.class files).

JRE (Java Runtime Environment) → so you can run what you write.

Tools like debuggers, profilers, and documentation generators.

Without JDK, you can’t develop Java apps — only run them.

2. JRE (Java Runtime Environment)

It’s the package to run Java applications.

Includes:

JVM (Java Virtual Machine) → executes bytecode.

Core Java libraries (collections, networking, IO, etc.).

End users who only need to run Java programs (not write them) just need JRE.

3. JVM (Java Virtual Machine)

The engine that makes Java platform-independent.

Takes compiled bytecode and translates it to machine code for the host OS.

Handles:

Memory management (via Garbage Collection).

Just-In-Time (JIT) compilation for faster execution.

Security checks (sandboxing for untrusted code).

Flow of Execution

You write Java code → MyApp.java.

JDK compiler (javac) compiles it → MyApp.class (bytecode).

JVM (inside JRE) loads and runs the bytecode on your OS.

Thanks to JVM, the same .class file runs on Windows, Mac, Linux, etc. without change.

👉 In short:

JDK = for developers (write + run).

JRE = for users (just run).

JVM = the core engine that makes Java portable.

