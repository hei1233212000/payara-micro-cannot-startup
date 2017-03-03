### This project show we cannot start the payara-micro(4.1.1.171.0.1) by maven

### Try run
>$ mvn clean package  

Then you will see an exception
> Caused by: java.lang.ClassNotFoundException: fish.payara.micro.boot.PayaraMicroBoot
    at java.net.URLClassLoader.findClass(URLClassLoader.java:381)
    at java.lang.ClassLoader.loadClass(ClassLoader.java:424)
    at java.lang.ClassLoader.loadClass(ClassLoader.java:357)
    ... 22 more