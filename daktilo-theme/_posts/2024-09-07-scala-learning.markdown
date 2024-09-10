---
layout: post
title:  "Scala: Learning Materials"
subtitle: "Dhaka 2024"
date:   2024-09-07 0:00:01
categories: [engineering]
---

Scala is a powerful and versatile language, combining object-oriented and functional programming concepts. Whether you're a beginner or looking to deepen your knowledge, here are some great resources to get started and continue your journey.

## 1. Rock the JVM

[Rock the JVM](https://rockthejvm.com/) offers some of the best Scala and functional programming courses. It is perfect for developers who want a structured, hands-on approach to learning Scala. Their courses cover a wide range of topics from Scala basics to advanced functional programming concepts.

### Code Sample from Rock the JVM

Here’s a simple example of a Scala class that mimics some of the concepts you'll learn from their beginner course:

```scala
class Person(name: String, age: Int) {
  def greet(): String = s"Hi, I'm $name and I'm $age years old."

  // Introducing a method with default parameters
  def greet(anotherPerson: String = "Anonymous"): String =
    s"Hi $anotherPerson, my name is $name."
}

val john = new Person("John", 30)
println(john.greet())          // Hi, I'm John and I'm 30 years old.
println(john.greet("Alice"))   // Hi Alice, my name is John.
```

## 2. Scala Exercises

[Scala Exercises](https://www.scala-exercises.org/) is an open-source platform that provides hands-on exercises for Scala learners. It's a great way to practice your skills while learning key concepts.

Useful Tips:
Start with the basics section to get familiar with Scala syntax.
Progress through functional programming exercises to sharpen your skills.

## 3. Tour of Scala
The official [Tour of Scala](https://docs.scala-lang.org/tour/tour-of-scala.html) is an excellent introduction to the core language features. This guide walks you through everything from basic syntax to more advanced features such as pattern matching and collections.

Code Sample
Here’s a snippet from their guide on pattern matching, a powerful Scala feature:



```scala
def matchTest(x: Int): String = x match {
  case 1 => "one"
  case 2 => "two"
  case _ => "many"
}

println(matchTest(1)) // one
println(matchTest(2)) // two
println(matchTest(3)) // many

```


## 4. Coursera - Functional Programming Principles in Scala
For a more academic introduction, consider the [Functional Programming Principles in Scala](https://www.coursera.org/learn/scala-functional-programming) course on Coursera, taught by Martin Odersky, the creator of Scala. This course provides an excellent foundation for understanding functional programming in Scala.

Example Code:
Here’s an example of a higher-order function in Scala that you’ll likely come across in the book:

```scala
def applyTwice(f: Int => Int, x: Int): Int = f(f(x))

val double = (x: Int) => x * 2
println(applyTwice(double, 3))  // 12
```

By using a combination of these resources, you’ll be well-equipped to master Scala and functional programming. Whether you prefer video tutorials, interactive exercises, or books, there’s something here for everyone. Happy learning!


### References:
- [Rock the JVM](https://rockthejvm.com/)
- [Scala Exercises](https://www.scala-exercises.org/)
- [Tour of Scala](https://docs.scala-lang.org/tour/tour-of-scala.html)
- [Functional Programming in Scala](https://www.manning.com/books/functional-programming-in-scala)
- [Coursera - Functional Programming in Scala](https://www.coursera.org/learn/scala-functional-programming)

