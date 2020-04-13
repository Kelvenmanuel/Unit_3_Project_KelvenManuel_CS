question 1: Write a Python program that asks the user for his first name and last name and a number (1, 100]. The output is a text file with as email addresses for the user:

```.py
text = input("Enter user first name, last name and a number: ")
output = text.split(", ")

text2 = open("output.txt", "w")
if int(output[2]) > 100:

    print("the number is not correct")
else :
    for i in range(1, int(output[2])+1):
        text2.write(output[0] + "." + output[1] + str(i) + "@uwcisak.jp\n")

text2.close()
```

question 2: Write a Python program that generates random passwords of length 20. The user provides how many passwords should be generated

```.py 
