---
layout: post
title:  "I'll never be writing an anemic domain model again and neither should you"
date:   2021-01-11 13:05:07 -0000
categories: ddd domaindrivendesign software
---
It's software, it's all about compromise... However, I will never be writing an anemic domain model again. Why you might ask? Well...

Let's take the example of a bank account and set some basic requirements

- Add funds
- Withdraw funds
  - Funds cannot be withdrawn if it will make the balance below the overdraft limit
- Set an overdraft limit

We'll take an anemic domain model and refactor it towards a rich domain model discussing the benefits as we go.

# State

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