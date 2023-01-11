# fizzbuzz
A program that prints fizz for numbers divisible by 3, buzz for numbers divisible by 5 and fizzbuzz for numbers divisible by 3 and 5

The code for the program:
for i in range(0,101):
    if i%3==0 and i%5==0:
        print("FizzBuzz")
    elif i%3==0:
        print("Fizz")
    elif i%5==0:
        print("Buzz")
    elif i%3==0 and i%5==0:
        print("FizzBuzz")
    else:
        print(i)
        
      
Download the python file and run it in python
