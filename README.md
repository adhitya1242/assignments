# assignments
## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

ans)  python is a langugage which supports bith procidure and object oriented programming 
	it supports us to do our general tasks and also high level tasks this why the python is called as as the 
	general purpose and high level language


Q2. Why is Python called a dynamically typed language?

ans)  python is called as dynamically typed language because python dosent show any error
	 even if u dont specify the type of the data you entered while coding it will do it ny itself 
	while runtime so the python is called as dynamically typed programming language 

Q3. List some pros and cons of Python programming language?

ans)  pros and cons of python programming language

      pros                                                                      cons
-> python language is easy to learn                               ->comparing to other compiled languages python is slow
   so its called as biginner friendly language                   
->python has a large community and it has maney libraries         ->pythons garbage colloction leades to potential memory loss
  it makes us comfortable to do our work on python 
  without any complexities
->python is a portable language and                               ->python language consumes high memory
  its a platform independed language                                       


Q4. In what all domains can we use Python?

ans)  in the following domains we can use python
      1) artificial intelligence
	2) mechine learning
      3) deep learning
	4) big data


Q5. What are variable and how can we declare them?

ans)  in any programmong language veriable is used to store some data temperorily or permanently
	
	there are some rules to declare veriable 
	1)a veriable name must start with a letter or underscore symbol
	2)veriable name cannot start with anumber
	3)veriable names are case sensitive i.e a & A are different 



Q6. How can we take an input from the user in Python?
ans)  in python we take input from user by using input() function

Q7. What is the default datatype of the value that has been taken as an input using input() function?

ans)  every time when we take the input from the user using input() function the default dtattype will be string 
	as the input() function accepts only string datatype

Q8. What is type casting?

ans)  converting of one datatype in to another is called typecasting in python
	we use some methods to do typecasating int() , float() , str() .... etc 

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

ans)  we cant take more than one input using just one input function 
	in  order to take more than one input we have to add other function
	called split() by using this we can tale multiple inputs from users
	with input() function

Q10. What are keywords?

ans)  in python keywords are those words which has reserved meaning 
	there are 33 keywords in python 

Q11. Can we use keywords as a variable? Support your answer with reason.

ans)  no we cant use keywords as a veriables in python because keywords 
	are the reserved words which are pre defined in python to accomplish the 
	perticular task so we cant use the keywords as veriables in python 

Q12. What is indentation? What's the use of indentaion in Python? 

ans)  in python indentation refers to the block of code 
	in other languages flower bracer or curly braces are used to repeasent the	
	block of code 

Q13. How can we throw some output in Python?
ans)  in order to throw an output in python we use a function called print
	syntax: print()

Q14. What are operators in Python?
ans) operaters in python helps us to perform verious sprcific operations 
	ex: arthamatic , aasigtnmemt , comparision , logical , identity , membership , bitwise


Q15. What is difference between / and // operators?

ans)  in python we can perform devision in three ways
	floating division ,floor division , modulo dividon 
	 / reprasents floating division we will get float values while division 
	// this reprasents floor division we will get only integer values by using 
	this symbol we call thos as integer devision also

Q16. Write a code that gives following as an output.
...
iNeuroniNeuroniNeuroniNeuron
```
ans)  name = iNEURON 
	repeat = iNEURON * 4
	print(repeat)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

ans)  number = int(input(enter any number))
	if number%2 == 0 :
		print(the number is even )
	else:
		print(the number is odd )


Q18. What are boolean operator?

ans)  the operators which returns the out put as true or false  is called as the 
	boolean operators in python


Q19. What will the output of the following?
```
1 or 0

true

0 and 0

false

True and False and True
 false

1 or 0 or 0

true
```

Q20. What are conditional statements in Python?

ans) conditional stastements in python are used to check the conditions and give solution according to the statements 
	there are 3 types of conditionla statements in python if ,elif ,else

Q21. What is use of 'if', 'elif' and 'else' keywords?

ans) the uses of if , elif , else 
	if : if is used to  check the condition if the condition is true the data given will be exicuted

	elif : elif is used to when if ststement is fales and there are multiple statements

	else : else is used the both statement in if ans elif are false

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

ans)  age = int(input("enter the age of candidate"))
	if age>=18 :
		print("i can vote")
	else:
		print("i cant vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
result = 0
for items in numbers:
	if items%2:
		result += item
print(risult)


```


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

ans) num1 = int(input("enter a number between 0 to 9 "))
     num2 = int(input("enter another number between 0 to 9"))
     num3 = int(input("enter another nuber between 0 to 9"))

	if (num1 >= num2) and (num2 >= num3):
		largest = num1
	elif (num2>= num1) and (num2 >= num3):
		largeat = num2
	else:
		largest = num3
	print("the largest number is", largest)


nQ25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
for items in numbers:
	if (number%5 == 0) and (number >500):
		print("the new list is", numbers)
