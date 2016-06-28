- title : Introduction to Functional Programming
- description : Introduction to Functional Programming
- author : Tomasz Heimowski
- theme : night
- transition : default

***

## F# CAMP

### Tomasz Heimowski

---

### Agenda

1. Introduction to the workshop series
2. What is Functional Programming
3. Why Functional Programming
4. Examples of functional concepts in C#

***

## Introduction to the workshop series

---

### Aim

* Learn F# language
* Discover Functional Programming concepts
* No prior F# / Functional Programming knowledge required - starting from scratch
* Have fun

---

### Format

* 4 meetings in July
    * first - introductory talk (this one)
    * 2nd, 3rd, 4th - combined talk + workshops (about 2.5 hours)
* Each workshop will cover concepts from the preceding talk
* If it rolls out nicely, there'll be a continuation of the series

---

### Real World Functional Programming

![real-world-functional-programming-cover](images/real-world-functional-programming-cover.jpg)

https://amzn.com/1933988924

---

### Source for presentations 

* Agenda - http://gda-gitlab-01.globalintech.pl/theimowski/fsharp-workshops
* This presentation - http://gda-gitlab-01.globalintech.pl/theimowski/fsharp-workshops-intro

Presentation made by [FsReveal](http://fsprojects.github.io/FsReveal) 

***

## What is Functional Programming

---

> Functional programming is a style of programming that emphasizes the evaluation of expressions, rather than execution of commands. The expressions in these languages are formed by using functions to combine basic values.

*Hutton*

---

### Statements vs Expressions

* Imperative style:
    * Statements
    * Commands
* Declarative style:
    * Expressions
    * Functional

https://twitter.com/mariofusco/status/571999216039542784

---

![imperatywny vs funkcyjny](images/imperative_functional.jpg)

---

### Brief history

* First functional language: LISP (1958)
* ML (1970) - generic functions
* OCaml (1996) - hybrid language
* F# came live with VS 2010 

Other important FP languages: Haskell, Erlang, Scala, Clojure

***

## Why Functional Programming

---

### Prevent unwanted side effects

    [lang=csharp]
    public int TestA()
    {
        return 5 + 6;
    }

    public int TestA()
    {
        return Sum(5, 6);
    }

    public int Sum(int a, int b)
    {
        var result = a + b;
        Console.WriteLine("Result is {0}", result);
        return a + b;
    }

*"Referential transparency"*

---

### Generalize common patterns

*"Parametric polymorphism"*

---

### Discover right abstractions

---

### Inhale concurrency

---

### Make code more testable

*"Isolation"*

---

### Twitter reactions

***

## Examples of functional concepts in C#

***

## Summary

***

## Next Week

### Basic concepts of Functional Programming (talk + workshop)