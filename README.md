This is "Hello World" Example for Java.

The structure HelloWorld package is like this:

example.java.helloworld/
|-- HelloWorld
|   `-- Main.java
|-- LICENSE
|-- Manifest.txt
`-- README.md
Compile class
For compile the main class for package, execute the follow command:

javac HelloWorld/Main.java
This generate the Main.class file into HelloWorld directory.

Run class
For run the main class for package, execute the follow command:

java -cp . HelloWorld.Main
This show the Hello world message.

Create a JAR file
For pack the main class for package as a JAR file, execute the follow command:

jar cfme Main.jar Manifest.txt HelloWorld.Main HelloWorld/Main.class
Run a JAR file
For run the JAR file packed, execute the follow command:

java -jar Main.jar
This show the Hello world message.

Reference
java - How to run a JAR file - Stack Overflow.
Setting an Application's Entry Point (The Java™ Tutorials > Deployment > Packaging Programs in JAR Files).
About
"Hello World" Example for Java

Topics
java hello-world helloworld
Resources
 Readme
License
 GPL-2.0 License
Releases
No releases published
Packages
No packages published
Contributors 2
@macagua
macagua Leonardo J. Caballero G.
@ashakdhe
ashakdhe
Languages
Java
100.0%
