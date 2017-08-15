// a python function to find the maximun of three numbers
def max(a,b,c)
if (a>b) and (b>c):
largest=a
elif(b>c) and (b>a):
largest=b
else:
largest=c
print(" the maximum of three numbers is {}".format(largest))
max(15,28,43)


// a python program to count the number of characters in a string
string=input(" enter the characters:")
char=0
for i in string :
char=char+1
print(" the no of characters in the string are {}".format(char))


// a python function that takes a list of words and returns the length of the longest one
def finding_the_longest_ word():
list1=input(" enter the words:")
longest=0
for words in list1.split():
if len(words)>longest:
longest=len(words)
return longest
print(finding_the_longest_word())


// a python program to verify if the string is a palindrome or not
s= input(" enter the string")
if(s==s[::1]):
print(" it is a palindrome")
else:
print(" it isnt a palindrome")


//fibonacci series
n=input(" enter the no of terms")
n1=0
n2=1
count=0
if n==1:
print(" the fibonacci series is {}".format(n1))
else:
print("the fibonacci series is")
while count<n:
print(n1,"," n2)
n3=n1+n2
n1=n2
n2=n3
count++


// a program to print nos divisible by 7 but not by 5
for number in range(2000,3200):
if (number%7==0) and (number%5!=0):
print(number,",")


//rock paper scissor game
p1=input(" enter your choice")
p2=input("enter your choice")
if (p1==p2)
 print(" it is a tie")
elif p1='rock':
 if p2='scissors':
 print(" p1 won")
 else:
 print(" p2 won")
elif p1='scissors':
 if p2= 'paper':
 print("p1 won")
 else:
 print("p2 won")
elif p1='paper':
 if p2='rock':
 print(" p1 won")
 else:
 print("p2 won")
 print(" start new game")
else: 
print(" invalid input")
 

 








