① Input, print and numbers

○Sum of three numbers
```.py
# This program reads two numbers and prints their sum:

a = int(input())
b = int(input())
c = int(input())
print(a + b + c)
```

○Square
```.py
# Read an integer:
a = int(input())
print(a * a)
```

○Apple sharing
```.py 
# Read the numbers like this:
n = int(input())
k = int(input())
# Example of division, integer division and remainder:
print(k // n)
print(k % n)
```

○Previous and next
```.py
# Read an integer:
a = int(input())
b = a +1 
c = a -1
print'the next number for the number', a, 'is', b
print 'the previous number for the number', a, 'is', c 
```

○Two timestamps
```.py
print 'Enter the hour minutes and seconds'
hour = int(input())
minutes = int(input())
seconds = int(input())
print 'Enter the second hour minutes and seconds'
hour2 = int(input())
minutes2 = int(input())
seconds2 = int(input())
minusseconds = ( hour * 3600 + minutes * 60 + seconds )-( hour2 * 3600 + minutes2 * 60 + seconds2)
print minusseconds
```

===================================================================

② Integer and float numbers

○Last digit of integer
```.py
#This program will get the last digit of an intiger/ input 
a = int(input("Enter a number: "))
last = a % 10
print "The last digit is", last
```

○Tens digits
```.py
n = int(input("Enter a number: "))
b = (n // 10) % 10
print b
```

○Car route
```.py
N = int(input("Enter the N kilometers: "))
M = int(input("Enter the M kilometers: ")) 
A=M%N
if A != 0:
  B = ((M//N)+1)
  print B
else:
  B = M/N
  print B 
```
○Digital Clock
```.py
n = int(input("Enter the min: "))
h = n // 60
m = n % 60
print h, m 
```
========================================================================

③ Conditions if then else
```.py
○ Minimum of two numbers
a = int (input("enter the number: "))
b = int (input("enter the number: "))
if a > b :
  print a
else:
  print b
```  
○Sign function
```.py
x = int (input("enter the number: "))
if x > 0 :
  print 1
elif x < 0: 
  print -1
else : 
  print 0
```  
○Rock move
```.py
a = int (input("enter 1st cell row1: "))
b = int (input("enter 1st cell col1: "))
c = int (input("enter 2nd cell row2: "))
d = int (input("enter : 2nd cell col2: "))

if a == c and b == d 
  print yes 
else : 
  print no 
```  
○Chocolate bar
```.py
n = int(input())
m = int(input())
k = int(input())

if (k % n == 0 and k / n < m) or (k % m == 0 and k / m < n):
    print "yes" 
else:
    print "no"
```

========================================================================

④ For loop with range
```.py
○Sum of N numbers
i = 0
n = 0 
sum = 0
print ("enter 10 numbers : \n")
for i in range(1, 11):
  print "enter Number",i 
  int(input())
  sum += n
  print n 
```
○The number of zeros
```.py
a=int(input("Enter a number:"))
number=0
for i in range(1,a+1):
  x= int(input("Enter a number:"))
  if x==0:
    number=number+1
print number
```
○Lost card
```.py
n = int(input("n: "))
lost = []

for i in range(n-1):
  i = int(input("n: "))
  lost.append(x)

for i in range(1, n+1):
  if lost.count(x) == 0:
    print("The lost card is: " + str(x))
```
