---
layout: page
title: "Practice Questions"
description: ""
---

# CAB201 Practice Written Questions

## Warmup
Write a method which takes no parameters, but which reads two numbers from stdin and returns the sum of those two numbers. The method signature is given below.

{% highlight C# %}
public static int sumInputs() {

}
{% endhighlight %}

## Question 1 (Easy)
Write a method which will count the number of occurrences of a character in a string. The method signature is given below.

{% highlight C# %}
public static int numCharInString(char c, string word) {

}
{% endhighlight %}

## Question 2 (Easy)
Given an array of n numbers, sum the entire array. The method should return a single value equal to the sum of the elements of the array. The method signature is given below.

{% highlight C# %}
public static int sumArray(int[] array) {

}
{% endhighlight %}

## Question 3 (Medium)
Given an array of n numbers, sum all of the elements of the array which are _odd_ numbers. This question should return the same thing as question 2. The method signature is given below.

{% highlight C# %}
public static int sumOddArray(int[] array) {

}
{% endhighlight %}

## Question 4 (Medium)
Given three numbers, return the number which has the highest value. First compare A against B, if A > B then it goes to compare A and C. If A > C, the A is largest number, else C is maximum number. On the other hand, if A < B in first comparison then second comparison happens between B and C, if B > C then B is largest otherwise C is largest number.

{% highlight C# %}
public static int largestNumber(int a, int b, int c) {

}
{% endhighlight %}

## Question 5 (Hard)
Write a method which will find the first non-repeated character in a String. Your function will accept a string and return the first non-repeated character. For example in the string `hello`, all characters except the `l`'s are repeated, but `h` is the first one. The method signature is given below:

{% highlight C# %}
public static char firstNonRepeatedCharInString(string word) {

}
{% endhighlight %}
