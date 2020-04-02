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
