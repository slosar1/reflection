# End of First Week
## 9/8/2017
###Ram, Ubuntu, Ip adress, Cmp, ls, pico, cd, cd .., cd ~, cat, vi, python, python 2, python3, hardrive, algorithm, and, or 

---

# End of Second Week
## 9/15/2017
What I learned last week:
1.) I learned the difference between rm and rmdir
2.) What Git add, Git commit -m "write something", Git pull, and Git push means
3.) How to add a tab: \t
4.) How to display something on a different line: \n
5.) What STRING is
6.) What python is
7.) What the difference between python2 znd python3
8.) How to clone
9.) How to say stuff to my self when I type python3 andwhatyou.have
	ex:   print ("Hello World")
	      print ("I like your shirt")
	      print ("what do you do for a living?")

10.) What the difference of input and raw input
11.) How to use numbers and use math in python

# End of week 3
## 9/22/17
What I learned last week:
1.) Import math
2.) Number = input("enter a number")
3.) Intnumber = int(number)
4.) Squareroot = math.sqrt(intnumber)
5.) types of functions:
	type, str, dir
6.) string manipulation
7.) reading material print function
8.) input function
	ex: name = input("what's your name?")
	    print("nice to meet you + name + "!")
	    age = input("your age?")
	    print("so, you are already " + age + " years old, " + name+ "!")
9.)  convert a python string to int and float
	The code:

	ex: str_a = '50'
	    b = 10
	    c = int(str_a0 + b
	    print("the value of c = ",c)

	The code of using float for converting a string:

	ex: str_a = '50.85'
	    b = 10.33
	    c = float(str_a) + b
	    print ("the value of c = ",c)
	
	The code:

	ex: str_lst = ['1', '2', '3']
	    int_lst = [int(x) for x in str_lst]
	    print (int_lst)

	The code for converting list items to float:

	ex: str_lst = ['10.505', '2.3', '3.99']
	    float_lst = [float(x) for x in str_lst]
	    print (float_lst)

	The code:

	ex: str_a = '5,123,00'
	    int_b = int(str_a.replace(',',''))
	    print ("the integer value", int_b)


# End of Week 4
##9/9/2017
What I learned this past week:

I learned a lot over this week, it has been challenging trying to figure out how to do some of the problems Mr. Gold gave me but he gave me
the power to get it done and I did. Here is a list of what I learned during this week:

1.) I learned how to use input a lot better using numbers
	ex: 	number1 = input("give me one between 1-10:")
		number2 = input("give me one between 1-10:")
            	number1 = int(number1)
        	number2 = int(number2)
   		print(number1 + number2)
 		average = (number1 + number2 / 2)
 		print("your average is")
 		print(average)

2.) how to use float and input in math

	ex:  	a = float(input("enter a:"))
 		b = float(input("enter b:"))
  		c = float(input("enter c:"))

	 	x = -1 * b

	  	product = x

	  	print("your x is =:")
  	 	print(x)


and a lot more.

# End of week 7 and 8
## 10/27/17
What I learned during the past two weeks:

1.) I learned how to use while loops(here is an example):
	for stumber in range(1,1000+1):
	if stumber %3==0:
		print("Burrito")
	elif stumber %5==0:
		print("Cheeto")
	elif stumber %3==0 and stumber %5==0:
		print("BurritoCheeto")
	elif stumber %7==0:
		print("Veto")
	elif stumber %3==0 and stumber %7==0:
		print("BurritoCheeto")
	elif stumber %5==0 and stumber %7==0:
		print("CheetoVeto")
	elif stumber %3==0 and stumber %5==0 and stumber %7==0:
		print("BurritoCheetoVeto")
	else:
		print(stumber)

2.) I also learned how to import random, use var, with a while loop(ex):

	import random

var = 1
secret = random.randint(1,1000+1)
while var == 1 :


	number = input("Please enter a number 1 through 1,000:")
	number = int(number)

	print(secret)
	if(number > secret):
		print("too high, not in range")
	elif(number < secret):
		print("too low, not in range")
	if(number == secret):
		print("you won!!!")
		var = 0

3.) I learned how to use count using a while loop(ex):

	count = 0
while(count < 10):
	count = count+1
while(count < 10):
	print(count)
print("Blastoof!")

4.)  I learned how to us "if" better and how to use "input" better(ex):

	temp = input("enter a temperature in fahrenheit")
temp = int(temp)
if(temp < 10.0):
	print("it is cold")
	temp = input("enter a temperature in fahrenheit")
	temp = float(temp)
print("ahh feels food")

5.) I also learned how to change a word that the person entered to a specific word(ex):

	story = input("Write a story:")
first_string = story
second_string = first_string.replace("the", "ermagherd")
third_string = second_string.replace("a", "ayyyyyy")
fourth_string = third_string.replace(".", "\a")
print(first_string, second_string, third_string, fourth_string)

6.) I also learned how to seperate someones name once typed in different lines(ex):

	person = input("What is your Full name:")
print("First Name", person)
print("Middle Name", person)
print("Last Name", person)

input = ('First Name')
print ('First Name' , str_('Middle Name"'))
input = ('Middle Name')
print = ('Middle Name',str_('Last Name'))
input = ('Last Name')

7.) I also learned how to use math and how to find an average(ex):

	print("You will give me five numbers and then I will give you your average.")

number1 = input("give me one number between 1-10:")
number2 = input("give me one number between 1-10:")
number3 = input("give me one number between 1-10:")
number4 = input("give me one number between 1-10:")
number5 = input("give me one number between 1-10:")
number1 = int(number1)
number2 = int(number2)
number3 = int(number3)
number4 = int(number4)
number5 = int(number5)
print(number1 + number2 + number3 + number4 + number5)
average = (number1 + number2 + number3 + number4 + number5 / 5)
print("your average is:")
print(average)
