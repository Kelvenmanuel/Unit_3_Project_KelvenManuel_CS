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
```PYTHON```is an interpreted, high-level, general-purpose programming language. Created by Guido van Rossum and first released in 1991, Python's design philosophy emphasizes code readability with its notable use of significant whitespace. Its language constructs and object-oriented approach aim to help programmers write clear, logical code for small and large-scale projects.( Python wikipedia )

### Why I decided to use python

Python is one of the most used/appreciated programming language by developers and software engineers. A big number of applications and webs that we use/enjoy today are because of Python. Python presents a versability and flexibility. Besides, abundant libraries, a collection of modules, and extensions that allow developers to create efficient programs or apps. Additionally, python can do complex tasks and possess a clean syntax and it is easy to learn. It is recommendable for Beginners and experienced programmers. It can connect to database systems, and also, read and modify files.

# T.E.L.O.S 
feasibility study:

  A feasibility study, in general, is a tool for determining whether you have what it takes to undertake a change or new project. In business, most managers make use of a particular feasibility tool called TELOS, an acronym for the five key areas that you need to consider in your study(business.tutsplus.com):

T - Technical - Is the project technically possible?
E - Economic - Can the project be afforded? Will it increase profit?
L - Legal - Is the project legal?
O - Operational - How will the current operations support the change?
S - Scheduling - Can the project be done in time? 
(Wiki/TELOS)

The user will be no longer unable to manage its supply of shoes. The App will be created to help the user to manage his shoe inventory. Using Python will be possible to create a program that will meet all the necessities of the user. That is, it will achieve all the items in the success criteria. The program will have a simple process of installation, without a large cust for the user. For the developer the cust for creating the program is manageable and this program will bring better benefits for the user.  The developer is using one of the most used programming languages that present no illegal issues, and there will be no divergence between the new system and any regulations. As I mentioned before the app will bring a large benefit for the user, and providing that is his first App the user should have or learn basic computational skills to manage it, but there is a certain question if the app can be used offline. Besides this, the work will certainly be automatized/improved. Considering the time that might be needed to finish the app, going through all the steps, the program can be done in time. 

### Qt Design
Qt Designer is Qt's tool for designing and building graphical user interfaces (GUIs) from Qt components. You can compose and customize your widgets or dialogs in a what-you-see-is-what-you-get (WYSIWYG) manner, and test them using different styles and resolutions.(designer-manual.html)

The Qt design is the tool that I am going to use to design the user interface for the app shoe. I will use this because is easy to manage, use, and We can obtain a good result with it. Moreover, We can use it with python. Providing that python is our main language to develop the app this a right tool.   

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

### First Draw of the user interface (Skecth)

Using the Qt design we could design the draw of the user interface for the Shoe. This proof our basic knowledge to manage the  Qt design and further we expect. the image below express the first draw of the user interface created by the developer and below the image there is the code in the python. Additionally, is necessary to create other program in python that would allow the user to run the program. However, it is necessary have this code for in the future running the interface. 

![sketch](firstsketch.png)

```.py
# -*- coding: utf-8 -*-

# Form implementation generated from reading ui file 'userface1.ui'
#
# Created by: PyQt5 UI code generator 5.14.1
#
# WARNING! All changes made in this file will be lost!

from PyQt5 import QtCore, QtGui, QtWidgets
from PyQt5.QtWidgets import QDialog


class userface1Form(object):
    def setupUi(self, userface1):
        userface1.setObjectName("userface1")
        userface1.resize(366, 441)
        userface1.setStyleSheet(
            "color: qlineargradient(spread:pad, x1:0, y1:0, x2:1, y2:0, stop:0 rgba(0, 0, 0, 255), stop:1 rgba(255, 255, 255, 255));\n"
            "background-color: qlineargradient(spread:pad, x1:0.615463, y1:0.642045, x2:0.8867, y2:0.846591, stop:0.142857 rgba(0, 0, 0, 255), stop:1 rgba(255, 255, 255, 255));")
        self.layoutWidget = QtWidgets.QWidget(userface1)
        self.layoutWidget.setGeometry(QtCore.QRect(40, 50, 261, 341))
        self.layoutWidget.setObjectName("layoutWidget")
        self.verticalLayout = QtWidgets.QVBoxLayout(self.layoutWidget)
        self.verticalLayout.setContentsMargins(0, 0, 0, 0)
        self.verticalLayout.setObjectName("verticalLayout")
        self.label1 = QtWidgets.QLabel(self.layoutWidget)
        self.label1.setMaximumSize(QtCore.QSize(200, 200))
        self.label1.setSizeIncrement(QtCore.QSize(100, 70))
        font = QtGui.QFont()
        font.setPointSize(20)
        self.label1.setFont(font)
        self.label1.setObjectName("label1")
        self.verticalLayout.addWidget(self.label1)
        self.label2 = QtWidgets.QLabel(self.layoutWidget)
        font = QtGui.QFont()
        font.setPointSize(20)
        self.label2.setFont(font)
        self.label2.setObjectName("label2")
        self.verticalLayout.addWidget(self.label2)
        self.button1 = QtWidgets.QPushButton(self.layoutWidget)
        self.button1.setMinimumSize(QtCore.QSize(50, 25))
        self.button1.setMaximumSize(QtCore.QSize(500, 50))
        self.button1.setStyleSheet(
            "color: qlineargradient(spread:pad, x1:0, y1:1, x2:0, y2:0.994, stop:0.142857 rgba(0, 0, 0, 255), stop:1 rgba(255, 255, 255, 255));")
        self.button1.setObjectName("button1")
        self.verticalLayout.addWidget(self.button1)
        self.button2 = QtWidgets.QPushButton(self.layoutWidget)
        self.button2.setMinimumSize(QtCore.QSize(100, 50))
        self.button2.setStyleSheet(
            "color: qlineargradient(spread:pad, x1:0, y1:1, x2:0, y2:0.994, stop:0.142857 rgba(0, 0, 0, 255), stop:1 rgba(255, 255, 255, 255));")
        self.button2.setObjectName("button2")
        self.verticalLayout.addWidget(self.button2)
        self.button3 = QtWidgets.QPushButton(self.layoutWidget)
        self.button3.setMinimumSize(QtCore.QSize(100, 50))
        self.button3.setStyleSheet(
            "color: qlineargradient(spread:pad, x1:0, y1:1, x2:0, y2:0.994, stop:0.142857 rgba(0, 0, 0, 255), stop:1 rgba(255, 255, 255, 255));")
        self.button3.setObjectName("button3")
        self.verticalLayout.addWidget(self.button3)

        self.retranslateUi(userface1)
        QtCore.QMetaObject.connectSlotsByName(userface1)

    def retranslateUi(self, userface1):
        _translate = QtCore.QCoreApplication.translate
        userface1.setWindowTitle(_translate("userface1", "Dialog"))
        self.label1.setText(_translate("userface1", "Welcome"))
        self.label2.setText(_translate("userface1", "Shoe App"))
        self.button1.setText(_translate("userface1", "Registration "))
        self.button2.setText(_translate("userface1", "Login"))
        self.button3.setText(_translate("userface1", "Exit "))
```

4.Evaluation 
==============================================



### What we can do to improve this program?

### References 

https://en.wikipedia.org/wiki/Python_(programming_language)

https://business.tutsplus.com/articles/can-we-really-do-it-how-to-conduct-a-telos-feasibility-study--cms-21442

https://en.wikipedia.org/wiki/TELOS_(project_management)

https://doc.qt.io/archives/qt-4.8/designer-manual.html

# Record of Tasks 
 
This table shows the 5 phases of the design: Planning, Design, Development, Test, and Implementation. 

| Task nº | Planned actions          |     Expected outcome            |   Time   |        Target Completion      | Criteria |
|---------|--------------------------|---------------------------------|----------|-------------------------------|----------|
|   1     | Planning:                | Acquire the first               | 15 min   | Did not come with clear       |     A    |
|         | Meet with the client for | requirements of the client      |          | questions, nor did the client |          |
|         | the first conversation   |                                 |          | have clear requirements       |          |
|         |                          |                                 |          |                               |          |
|   2     | Development: Create      | A phyton scrip that allows      |  1 hour  | Developed functions such as   |          |
|         | a secure login system    | encrypted login of a user       |          | "log in" & "register", using  |     A    |
|         | using phyton             |                                 |          | an encrypted password system. |          |
|         |                          |                                 |          | Need to further inquire as to |          | |         |                          |                                 |          | what "exit" entails           |          | 
|  3      | Planning:                | The success criteria for the    |  20 min  | Clear questions for the       |    A     |
|         | Meet with client for the | Iventory or Shoe App, details   |          | client, developer proposals   |          |
|         | 2nd conversation         | about the design & sytem of     |          | for the App                   |          | |         |                          | the App                         |          |                               |          | 
|  4      | Design:                  | A basic interface for the       | 30 min   | based on some examples create |    A     |
|         | Make a basic skecth draw | application, defining the basics|          | a sketch for the application  |          |
|         | of the interface for the | inputs, labels and buttons      |          | ask for feedback to the       |          |
|         | application              |  within the app                 |          | client                        |          |
|         |                          |                                 |          |                               |          |
|  5      | Planning:                | general feedback about the      |  25 min  | the skecth was already made as|    A     |
|         | Meet with client for the |first draw for the user interface|          | a draw. Present the sketh for |          |
|         | 3rd conversation         |client give arguments in the way |          | cleint view                   |          |
|         |                          |that developer can improve the   |          |                               |          |
|         |                          |the user interface               |          |                               |          |     


