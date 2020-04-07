#Question 1:
#Write a Python program that accepts a string and calculate the number of digits and letters.
```.py
countingnum = 0
countinglet = 0
word = [chr for chr in input()]
for char in word:
    if char.isdigit():
            countingnum+=1
    if char.isalpha():
            countinglet+=1
print("Letters", countinglet)
print("Digits", countingnum)
```
Question 2:
#With a given integral number n, write a program to generate a dictionary that contains (i, i*i) such that i is an integral number between 1 and n (both included). The program should print the dictionary.

```.py
n = int(input())
Dict = {}
for i in range(1,n+1):
        Dict[i] = i ** 2
print(Dict)
```

Question 3:
Write a program that accepts a comma separated sequence of words as input and prints the words in a comma-separated sequence after sorting them alphabetically.

```.py
from string import ascii_lowercase
word = input().split(",")
text = []

for a in ascii_lowercase:
    for i in range(len(word)):
        if word[i][0] != a:
            continue
        else:
            text.append(word[i])

print(','.join(text))
```

Question 4:
Define a class which has at least two methods: 
```.py
class Strings():
    def __int__(self):
        self.string = ""

    def Getting(self):
        self.string = input()

    def PrintString(self):
        print(self.string.upper())

string = Strings()
string.Getting()
string.PrintString()
```

Question 5:
Write a Python program to calculate a dog's age in dog's years. Go to the editor
Note: For the first two years, a dog year is equal to 10.5 human years. After that, each dog year equals 4 human years.

```.py
n = int(input())

if n <= 2:
    dogage = n * 10.5
elif n > 2:
    dogage = 2 * 10.5 + (n-2) * 4

print(dogage)
```
