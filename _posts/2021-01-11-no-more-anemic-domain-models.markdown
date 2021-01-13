---
layout: post
title:  "I'll never be writing an anemic domain model again and neither should you"
date:   2021-01-11 13:05:07 -0000
categories: ddd domaindrivendesign software
---
It's software, it's all about compromise... However, I will never be writing an anemic domain model again and neither should you. Why you might ask? Well...

Let's start with a quote from Martin Fowler on [anemic domain models](https://www.martinfowler.com/bliki/AnemicDomainModel.html).

> "The fundamental horror of this anti-pattern is that it's so contrary to the basic idea of object-oriented designing; which is to combine data and process them together. The anemic domain model is just a procedural style design, exactly the kind of thing that object bigots like me ... have been fighting since our early days in Smalltalk. What's worse, many people think that anemic objects are real objects, and thus completely miss the point of what object-oriented design is all about."



Let's take the example of a bank account and set some basic requirements

- Add funds
- Withdraw funds
  - Funds cannot be withdrawn if it will make the balance below the overdraft limit
- Set an overdraft limit

We'll take an anemic domain model and refactor it towards a rich domain model discussing the benefits as we go.

# State

Is important

# Encapsulation

# Testability


``` csharp
public class Test
{
  public class Test()
  {

  }
}
```
