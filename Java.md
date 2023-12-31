## Java
~~~
  <script>
  class Main {
    public static void main(String[] args) {
        System.out.println("Hello, world!");
    }
  <script>
~~~

### 1. outline

- An object-oriented programming language developed by Sun Microsystems in 1995. The creator is James Gosling. When Oracle acquired Sun Microsystems in 2010, it owned the copyright for Java. Currently, OpenJDK is GPL2, but Oracle JDK distributed by Oracle is a commercial license, and the payment policy has been strengthened since January 2019. Java EE is owned by the Eclipse Foundation. The Java language is being developed in the Java Community Process (JCP) since J2SE 1.4.

### 2. classification

- Java Standard Edition (Java SE)
The standard edition that most people encounter the most. It provides core APIs and functions of Java. See also the JDK entry.
- Jakarta EE, formerly Java EE (Java Enterprise Edition / J2EE)
This edition is specialized for server pages operated by companies. It contains technologies related to web application servers, including JSP and servlet.
- Java ME (Java Micro Edition / J2ME)
It is a lightweight edition specialized for embedded system environments such as feature phones, PDAs, set-top boxes, and sensors.

### 3. characteristic

- The biggest feature of Java is that it is a platform independent language. Unlike C/C++ compilers that directly compile and link source codes into machine code, Java compilers generate bytecode class files (. am.


### 3.1. Comparison with C and C++
- As object-oriented features were added to the existing C, it was developed as an object-oriented language from the beginning, unlike C++, where there were many conflicts between low-level and high-level concepts in the use of the language.
- Java is not strictly an object-oriented language. Primitive types are not treated as objects. A language that treats everything as an object is called pure object-oriented, and languages ​​that support it include Python, Ruby, and Smalltalk.
- As with [C-type programming languages](https://en.wikipedia.org/wiki/List_of_C-family_programming_languages), it has a syntactic structure similar to that of C/C++. However, there are many areas where Java is much more widely used than C/C++.

### 3.2 JDK provider
- https://whichjdk.com/
- [ORACLE](https://www.oracle.com/java/technologies/downloads/) : Only the most recent version released is publicly available during general support dates, otherwise privately provided to customers with subscriptions to Oracle services.
- [OpenJDK](https://openjdk.org/install/) : Only the latest released version is provided, otherwise only source is provided.
- [AzulC](https://www.azul.com/downloads/?package=jdk#zulu) : Provides all versions after 6, free for business use or paid technical support
- [Temurin (Adoptium)](https://www.azul.com/downloads/?package=jdk#zulu) : courtesy of the Eclipse Foundation, available in LTS 8, 11, 17 and newer versions
- [Microsoft JDK](https://learn.microsoft.com/ko-kr/java/openjdk/download) : Available in LTS 11 and 17, primarily as a JDK for our own Azure cloud environment.
- [JBR](https://github.com/JetBrains/JetBrainsRuntime) : JetBrains internally uses JDK to develop IDE, and only runtime is included in IDE and provided.
- [BellSoft Liberica JDK](https://bell-sw.com/pages/downloads/?) : JDK designated by Spring as an official runtime. Like Zulu above, it can be used commercially for free, and technical support is provided for a fee.
- [IBM Semeru Runtime](https://developer.ibm.com/languages/java/semeru-runtimes/downloads/) : A JDK developed by IBM and provided exclusively for the IBM Cloud.
- [Amazon Corretto](https://aws.amazon.com/ko/corretto/) : This is a JDK suitable for use in AWS, which was born as a result of Oracle's change in licensing policy. As with other clouds, large cloud companies are distributing JDKs because of concerns over license conflicts when using JDKs in the cloud.
- [Alibaba Dragonwell](https://dragonwell-jdk.io/) : A JDK created by Alibaba, which is known for contributing to OpenJDK more than expected. Therefore, China is encouraging Java development through this JDK. If not for that reason, there are many options, so it is recommended not to use it except for Java development in China.
- [SapMachine](https://github.com/SAP/SapMachine/releases) : A JDK made by SAP, completely SAP specific. Therefore, there is nothing to see unless it is SAP development.
- [Red Hat OpenJDK](https://developers.redhat.com/products/openjdk/download) : This is a JDK made by Red Hat. It runs on Red Hat Linux and its base, CentOS, and is widely used when installing OpenJDK in Korea without knowing it. In other words, if you search to install OpenJDK on CentOS or Red Hat, it is likely that this is the JDK to be searched and installed. It does not work on anything other than Red Hat-based Linux. However, the official site additionally provides a Windows version.

### 4. List of famous JVM languages
- closer
- Groovy: A dynamically typed language that combines features of Python, Ruby, and SmallTalk with Java. Appeared in 2003. It is the primary language for Gradle package management.
- JRuby: A language implementation of most of Ruby in Java. It is also compatible with Java.
- Jython: A Java implementation of Python. It runs on the JVM, so it is possible to use Java classes and JARs with Python modules.
- Kotlin: JVM language developed by JetBrains, creators of IntelliJ IDEA. It was designated as the official language of Android at Google I/O 2017.[9]
- Rhino: A JavaScript engine running on the JVM, developed 100% Java by the Mozilla Foundation. It can be developed using both JavaScript and Java APIs. It's built into Java 7.
- Nashorn: A JavaScript engine that runs on top of another JVM. It appeared with Java 8. However, it is planned to be removed from Java 11 and completely removed from Java 15. By the way, Nashorn is German for Rhino. After removal, GraalVM takes over.
- scalar
