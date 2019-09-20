---
layout: post
title: More Programming
categories: Project
---

## Programming Week 2

This week I did more programming in C#.
I did loops, learned casting and constants and used a loop.

```csharp
    class Program
    {
        static void Main(string[] args)
        {

            Console.WriteLine("Enter a number: ");
            int num = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("How many times do you want to multiply it? ");
            int times = Convert.ToInt32(Console.ReadLine());

            for (int x = 1; x <=times; x++)
            {

                int tempnum = x + 1;
                Console.WriteLine(x + " times " + num + " is " + (num * tempnum));

            }

            Console.ReadLine();

        }
```
