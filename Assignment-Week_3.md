JDK stands for Java Development Kit. JDK offers more software tools that allows us to actually write, compile, and debug programs alongside with being able to run them.
JRE stands for Java Runtime Environment. JRE contains all the java language API (Application Programming Interface), class libraries, and it allows us to run java applications.
JVM stands for Java Virtual Machine. JVM is a engine which provides runtime environment to drive the Java Code or applications. JVM essentially allows us to write programs that speak to our machines. It translates java programming and bytecode into machine language.

The JDK, JRE, and JVM are essentialy building blocks for each other. The JVM is the foundation which allows us to send instructions to the machine. The JVM is built into the JRE because you need to be able to instruct the machine to run java apps. The JRE is built into the JDK so the additional tools in the package can be used to help run java apps. The JDK can write and compile java programs written on any type of machine since java language is the same everywhere. The java program is then run by the JRE which is translated into machine language by the JVM. The JVM is readily available on several different operating systems so the same files written on say Windows can also be run on Linux.


```
/**
*Title: "Hello World" for Microsoft Windows
*Author: Oracle
*Date: 2019
*Code version: 1.0
*Availability: https://docs.oracle.com/javase/tutorial/getStarted/cupojava/win32.html
* The HelloWorldApp class implements an application that
* simply prints "Hello World!" to standard output.
*/
class HelloWorldApp {
public static void main(String[] args) {
System.out.println("Hello World!"); // Display the string.
}
}
```
If you are starting fresh, you need to JDK to first write the code for the Hello World Program and then compile it. If you already have the program files compiled and written in java language, then you only need the JRE to run the program. If the java program is already translated to java bytecode, then you only need the JVM to run it.


How are exceptions handled between the JDK, JRE, and JVM? For example, If you are writing code and you run into an exception, is it caught by the JDK before being run by the JRE? Likewise, if you have a java application that contains errors and exceptions, is it caught by the JRE before it reaches the JVM? And if exceptions do reach the JVM how are they handled?
