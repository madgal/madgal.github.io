---
layout: post
title: "Python Code Samples"
date: 2016-02-21 
categories: CodingExperience CodeSamples Python 
---
This is the FizzBuzz program written in python.

The purpose is to print the numbers 1 to 100 and if the number is divisible by 3 print Fizz, if it is divisible by 5 print Buzz, and if it is divisible by both print FizzBuzz. 
{% highlight python %}
   
def FizzBuzz():

	for i in range(0,100):

		if i%15 ==0: 
			print "FizzBuzz"
		elif i%3==0:
			print "Fizz"
		elif i%5=0:
			print "Buzz"
		else
			print "FizzBuzz"

FizzBuzz()
{% endhighlight %}
