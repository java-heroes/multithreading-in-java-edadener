# What is a Java Thread and Why is It Used?
A thread, in the context of Java, is the path followed when executing a program. All Java programs have at least one thread, known as the main thread, which is created by the Java Virtual Machine (JVM) at the program’s start, when the main() method is invoked with the main thread.

In Java, creating a thread is accomplished by implementing an interface and extending a class. Every Java thread is created and controlled by the java.lang.Thread class.

A single-threaded application has only one thread and can handle only one task at a time. To handle multiple tasks in parallel, multi-threading is used: multiple threads are created, each performing a different task.

# What is Multithreading?
Multithreading is a programming concept in which the application can create a small unit of tasks to execute in parallel. If you are working on a computer, it runs multiple applications and allocates processing power to them. A simple program runs in sequence and the code statements execute one by one. This is a single-threaded application. But, if the programming language supports creating multiple threads and passes them to the operating system to run in parallel, it’s called multithreading.

# How does Java Support Multithreading?
Java has great support for multithreaded applications. Java supports multithreading through Thread class. Java Thread allows us to create a lightweight process that executes some tasks. We can create multiple threads in our program and start them. Java runtime will take care of creating machine-level instructions and work with OS to execute them in parallel.

# Synchronized in Java
Multi-threaded programs may often come to a situation where multiple threads try to access the same resources and finally produce erroneous and unforeseen results. 

So it needs to be made sure by some synchronization method that only one thread can access the resource at a given point of time.

Java provides a way of creating threads and synchronizing their task by using synchronized blocks. Synchronized blocks in Java are marked with the synchronized keyword. A synchronized block in Java is synchronized on some object. All synchronized blocks synchronized on the same object can only have one thread executing inside them at a time. All other threads attempting to enter the synchronized block are blocked until the thread inside the synchronized block exits the block.

## Following are some of the common advantages of multithreading :
* Enhanced performance by decreased development time
* Simplified and streamlined program coding
* Improvised GUI responsiveness
* Simultaneous and parallelized occurrence of tasks
* Better use of cache storage by utilization of resources
* Decreased cost of maintenance
* Better use of CPU resource

## Multithreading does not only provide you with benefits, it has its disadvantages too. Let us go through some common disadvantages :
* Complex debugging and testing processes
* Overhead switching of context
* Increased potential for deadlock occurrence
* Increased difficulty level in writing a program
* Unpredictable results



## - REFERENCES


[Reference 1](https://www.journaldev.com/1079/multithreading-in-java)

[Reference 2](https://www.geeksforgeeks.org/synchronized-in-java/)

[Reference 3](https://www.multisoftvirtualacademy.com/blog/common-advantages-and-disadvantages-of-multithreading-in-java/)

[Reference 4](https://www.w3schools.com/java/java_threads.asp)


[Reference 5](https://www.eginnovations.com/blog/java-threads/)


