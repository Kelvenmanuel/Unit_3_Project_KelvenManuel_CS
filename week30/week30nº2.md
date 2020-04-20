② Narrative programming with OOP practice. The following paragraph is a narration of a program developed by Sandi Metz (She is an awesome programmer in Ruby). 
Your task is to write the code that corresponds to that narration. 


In the application for a bicycle tour company, there is a class called Bicycle, with 3 instance attributes: size, chain, and tire size. 
The constructor also includes a call to the method post_initialize that takes the tire size and prints the circumference of the wheel. The instance attributes have default values as: tyre size=29 inches, chain=11 speed, and size= M. 
In this class there is another method called spares which prints the tyre size and the chain size. The class also has a class attribute called number of bicycles which is increased by one every time a new object of this class is created. 


In this application there is another class called Mountain Bike that inherits from the Bicycle class. 
It has two additional instance attributes: front fork and rear shock, which indicate the travel distance in millimeters of the front and back suspension of the mountain bike.  
The default tyre size for a mountain bike is 27.5. The default front fork is 100 mm and rear shock is 80 mm. The class has a class attribute for the number of mountain bikes.


In the main application there is a list that stores the objects of bicycles and mountain bikes created.

```.py
import math

class bicycle:
    def __int__(self, size, chain=11, tire_size=29):
        self.size = size
        self.chain = chain
        self.tire_size = tire_size

    def post_initializer(self):
        circumference = 2+math.pi*self.tire_size/2
        print(circumference)

    def spares(self):
        print(self.chain, self.tire_size)

    def add(self):
        bicycle.number += 1
        print(bicycle.number)

M = bicycle("M", chain=11, tire_size=29)
M.post_initializer()
M.spares()
M.add()

class mountainbike(bicycle):
    number_2 = 0
    def __int__(self, size, chain, tire_size=29, frontfork=100, rearshock=80):
        super().__int__(size, chain, tire_size)
        self.frontfork = frontfork
        self.rearshock = rearshock

    def add2(self):
        mountainbike.number_2 += 1
        print(mountainbike.number_2)


A = bicycle("M", chain=11, tire_size=27., frontfork=100, rearshock=80)
A.post_initializer()
A.spares()
A.add2()

```
