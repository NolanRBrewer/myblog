---
title: Fizzbuzz
date: 2022-01-27 19:20:10
tags:
---
## description 
Print a range of numbers. If divisable by three print 'Fizz'. If divisable by 5 print 'Buzz', but if divisable by both 3 and 5 print 'Fizzbuzz'.

## code
```
#Fizz Buzz
for i in range(16):
    if i == 0:
        print(i)
    elif (i%3 == 0) and (i%5 == 0):
        print ("Fizzbuzz")
    elif i%3 == 0:
        print("Fizz")
    elif i%5 == 0:
        print("Buzz")
    else:
        print(i)
```