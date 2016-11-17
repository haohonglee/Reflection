# Reflection

A program that can analyze the capabilities of classes is called reflective.

1. What is reflection?

"Reflection is commonly used by programs which require the ability to examine or modify the runtime behavior of applications running in the Java virtual machine." This concept is often mixed with introspection. The following are their definitions from Wiki:
Introspection is the ability of a program to examine the type or properties of an object at runtime.
Reflection is the ability of a program to examine and modify the structure and behavior of an object at runtime.
From their definitions, introspection is a subset of reflection. Some languages support introspection, but do not support reflection, e.g., C++.

2. Why do we need reflection?

Reflection enables us to:

Examine an object's class at runtime
Construct an object for a class at runtime
Examine a class's field and method at runtime
Invoke any method of an object at runtime
Change accessibility flag of Constructor, Method and Field etc.
Reflection is the common approach of famework.

For example, JUnit use reflection to look through methods tagged with the @Test annotation, and then call those methods when running the unit test. (Here is a set of examples of how to use JUnit.)

For web frameworks, product developers define their own implementation of interfaces and classes and put is in the configuration files. Using reflection, it can quickly dynamically initialize the classes required.
