### Unit_3_Project_KelvenManuel_CS

 SHOE APP ( INVENTORY ) 
===========================

A SHOE Inventoy APP created using Python


Contents
==============================================
  1. [Planning](#planning)
  1. [Design](#design)
  1. [Development](#development)
  1. [Evalution](#evaluation)
  

 1.Planning
==============================================

### Definition of the problem 
In 2020. A business Man, called irving fang, is running a shoes company. The company name is Shoe with fang and they are responsible for selling high level and Quality shoes. Mr. Irving has a significant number of supply, and does not know how to manage it. Besides, He presents a variety of brands with diffeent shoe colorway, prices and volatility. 

### Proposed Solution 
Create an Application of software/App using the program language ```PYTHON```, one of the top-picked programming languages of most universities and industries. The purpose of this application is to assist the user to manage their shoe supply. Where this App will meet the needs of the company, organizing the shoe in a set of criteria given by the user(Mr. Irving), such as brand, colorway, and quantity. Moreover, this app will allow the user to give the price of the shoe, edit their data and delete unnecessary or outdated information about shoes.  

### Success criteria

1. Identify the brand and the country that produced the Shoe;
2. Information about how many shoe the iventory has;
3. Identify the colorway of every shoe; 
4. Recognize/provide the current price, past and retail price of every shoe;
5. Display the volarity of every shoe;
6. Provide the amount of sales that every shoe has;
7. Show the last time that the shoe was used;
8. Every shoe can be edited and deleted.



 2.Design 
==============================================

### python
```PYTHON```is an interpreted, high-level, general-purpose programming language. Created by Guido van Rossum and first released in 1991, Python's design philosophy emphasizes code readability with its notable use of significant whitespace. Its language constructs and object-oriented approach aim to help programmers write clear, logical code for small and large-scale projects.[1]

### Why I decided to use python

Python is one of the most used/appreciated programming language by developers and software engineers. A big number of applications and webs that we use/enjoy today are because of Python. Python presents a versability and flexibility. Besides, abundant libraries, a collection of modules, and extensions that allow developers to create efficient programs or apps. Additionally, python can do complex tasks and possess a clean syntax and it is easy to learn. It is recommendable for Beginners and experienced programmers. It can connect to database systems, and also, read and modify files.

# T.E.L.O.S 
feasibility study:

[2]. A feasibility study, in general, is a tool for determining whether you have what it takes to undertake a change or new project. In business, most managers make use of a particular feasibility tool called TELOS, an acronym for the five key areas that you need to consider in your study:

T - Technical - Is the project technically possible?
E - Economic - Can the project be afforded? Will it increase profit?
L - Legal - Is the project legal?
O - Operational - How will the current operations support the change?
S - Scheduling - Can the project be done in time? [3]

The user will be no longer unable to manage its supply of shoes. The App will be created to help the user to manage his shoe inventory. Using Python will be possible to create a program that will meet all the necessities of the user. That is, it will achieve all the items in the success criteria. The program will have a simple process of installation, without a large cust for the user. For the developer the cust for creating the program is manageable and this program will bring better benefits for the user.  The developer is using one of the most used programming languages that present no illegal issues, and there will be no divergence between the new system and any regulations. As I mentioned before the app will bring a large benefit for the user, and providing that is his first App the user should have or learn basic computational skills to manage it, but there is a certain question if the app can be used offline. Besides this, the work will certainly be automatized/improved. Considering the time that might be needed to finish the app, going through all the steps, the program can be done in time. 



3.Development 
==============================================

Python Appication
```.py
ser = {'username': None, 'password-hash': None, 'Salt': None}

print("1 - Register ")
print("2 - Log in ")
print("3 - Exit")
opt = 10
while opt > 3:
    opt = int(input("Enter option (1, 2, 3) "))

# Registration

username = input("enter username: ")

confirmed = False
while not confirmed:
    password = input('Enter password: ')
    c_password = input('confirm your password: ')

    # confirmed = True if password == c_password else False
    if password == c_password:
        confirmed = True

print("Password confirmed")
```
This code above is and exemple of python application. Where we successfully create a program that asks for registration of the user. Additionally if possible to input a password and confirm it. The program, in the beginning, asks for 3 options: Registration, login, and Exit. In option registration, the user will be asked to input the username and password, and the password can be successfully confirmed.This is important because is one of the first steps for the inventory  


4.Evaluation 
==============================================



### What we can do to improve this program?

### References 

[1]. “Python (Programming Language).” Wikipedia, Wikimedia Foundation, 23 Feb. 2020, en.wikipedia.org/wiki/Python_(programming_language).

[2]. Jun, Lisa Jo Rudy25, et al. “Can We Really Do It? How to Conduct a TELOS Feasibility Study.” Business Envato Tuts , 25 June 2014, business.tutsplus.com/articles/can-we-really-do-it-how-to-conduct-a-telos-feasibility-study--cms-21442.

[3]. “TELOS (Project Management).” Wikipedia, Wikimedia Foundation, 20 Oct. 2016, en.wikipedia.org/wiki/TELOS_(project_management).

# Record of Tasks 
 
This table shows the 5 phases of the design: Planning, Design, Development, Test, and Implementation. 

| Task nº | Planned actions          |     Expected outcome            |   Time   |        Target 0pmpletion      | Criteria |
|---------|--------------------------|---------------------------------|----------|-------------------------------|----------|
|   1     | Planning:                | Acquire the first               | 15 min   | Did not come with clear       |     A    |
|         | Meet with the client for | requirements of the client      |          | questions, nor did the client |          |
|         | the first conversation   |                                 |          | have clear requirements       |          |
|   2     | Development: Create      | A phyton scrip that allows      |  1 hour  | Developed functions such as   |          |
|         | a secure login system    | encrypted login of a user       |          | "log in" & "register", using  |     A    |
|         | using phyton             |                                 |          | an encrypted password system. |          |
|         |                          |                                 |          | Need to further inquire as to |          | |         |                          |                                 |          | what "exit" entails           |          | 
|  3      | Planning:                | The success criteria for the    |  20 min  | Clear questions for the       |    A     |
|         | Meet with client for the | Iventory or Shoe App, details   |          | client, developer proposals   |          |
|         | 2nd conversation         | about the design & sytem of     |          | for the App                   |          | |         |                          | the App                         |          |                               |          | |         |                          |                                 |          |                               |          |
|         |                          |                                 |          |                               |          |




