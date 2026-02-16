NIKUNJ DEEP UPADHYAY
25070123081
ENTC B1
EXPERIMENT 7 STUDY OF CONDITIONAL STATEMENT IN PYTHON.

THEORY-
In this experiment we are going to discuss while loop and its uses we had to declare a variable, then while loop starts with a condition then the iteration takes place. It is used to find factorial of a number by declaring condition of n>0 for i=n and i*=n and n-=1. It is used for finding fibonacci series like first we had to give 0 and 1 then then we had to proceed with the sum of last two number given and it will give the desired sum upto the limit of our choice for example we had given limit 4 then the output would be 0 1 1 2 3. It is used to check for a reverse of a number if we had given any number like 1234 then using while loop we can reverse that number to 4321 and if on reversing we are getting same number like 121 on reversing is same as 121 then that number is known as palindrome number. The same we can do with the string like madam is a palindrome string. We can use while loop for counting number of digits in a number for example in 123 we had three digits. We can also use while loop for searching any element in an array. If we want to print only odd numbers or only even numbers in a specified range then we can use while loop to do it.

ALGORITHM-
i=1 # declaration of i takes place
while i<=5: #condition that i has to be less than 5
  print(i) # will print 1 to 5 using while loop.
  i+=1 #each time i value will be incremented till it reach 5.
1  # the output
2
3
4
5

n=int(input("enter a number:")) # giving input a number.
i=1 #initializing i
while n>0: #condition given in a while loop
  i*=n # n given as input will be multiplied with i and will be stored in it until n>0
  n=-1 # n will be decremented until it is greater than 0
print(i)
# suppose n=5
output will be 120 which is factorial of 5

n=int(input("enter a number:")) # giving input a number.
a=0 # initialize a
b=1 # initialize b
i=1 # initialize i
while i<=n: # giving condition for i has to less than n
  print(a,end="") # will print a initially
  c=a+b # will store a+b value in c until loop works
  a=b # b value will be store in a until loop worls
  b=c # c value will be store in b until loop works
  i+=1 # i will be incremented until it is less than n 
# suppose n is 4 output will be 0 1 1 2 3 a fibbonacci series 

limit=int(input("enter the limit:")) #we given input a limit
a=0 # initializing a as 0
b=1 # initializing b as 1
while a<=limit: # giving condition in a while loop
  print(a,end="") # a will be printed until the condition.
  a,b=b,a+b # b will be store in a and a+b will be store in b
# if we given limit as 4 then output will be 0 1 1 2 3

n=int(input("enter the number")) # giving input to a user
rev=0 # initializing rev with 0
while n>0: # condition in a while loop
  d=n%10 # remainder of n will be stored in d
  rev=rev * 10 +d # each time on storing d it will be added to rev*10 and will store in rev.
  n//=10 # n will be replace with its quotient until it satisfy loop condition
print(rev) # reversed number will be printed
# suppose n is 134 output will be 431

n=int(input("enter the number")) # giving input to a user
rev=0 # initializing rev with 0
while n>0: # condition in a while loop
  d=n%10 # remainder of n will be stored in d
  rev=rev * 10 +d # each time on storing d it will be added to rev*10 and will store in rev.
  n//=10 # n will be replace with its quotient until it satisfy loop condition
print(rev) # reversed number will be printed
# suppose rev is same as n for example 121 so it is a palindrome number else not.

s=input("enter the string:") # giving input as string
rev=s[::-1] #obtaining reverse of a string
if s==rev: #checking condition
  print("palindrome")
else:
  print("not palindrome")
# suppose string input as madam output will be palindrome.

n=int(input("enter the number") # taking input of a number.
count=0 # initializing count with 0
while n>0: # condition in while loop
  n//=10 # quotient of n will be stored in n until satisfy loop condition
  count+=1 # count will be incremented by 1 
print(count) # will give number of digits in a number
# suppose input number is 4321 output will be 4

i=0 # initializing i with 0
while i<10: # condition in a while loop
 i+=1 # i will be incremented with +1
 if i%2==0:  # here continue statement after this condition will priint only odd number
  continue
print(i)
# output would be 
1 3 5 7 9

n=[10,20,30,40] # array has been declared in n
key=int(input("enter a number")) # number input to key
i=0 # initializing i with 0
while i < len(n): condition of i in while loop
  if n[i] == key: # checking if key found in n 
    print("element found at index",i)
    break # program will terminate if key found in n.
  i+=1 # i will be incremented until key does not found
else: # if key does not found in n it will be switch to else 
 print("not found") 
 # suppose key input is 20 output will be element found at index 1



