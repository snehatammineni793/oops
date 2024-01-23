#1 queoops

from random import *

class Dice:
    def __init__(self,sides):
        self.sides=sides
        
    def roll_dice(self):
        print(randint(1,self.sides))
        

d=Dice(8)
d.roll_dice()

#2queoops

import math

class circle:
    def __init__(self,radius):
        self.radius=radius
        
    def area(self):
        return math.pi*self.radius*self.radius
        
    def perimeter(self):
        return 2*math.pi*self.radius

c=circle(5)
print(c.area())

#3queoops
class book:
    def __init__(self,title,author,price):
        self.title=title
        self.author=author
        self.price=price
        
    def show_details(self):
        print(self.title)
        print(self.author)
        print(self.price)
        
b=book('wof','apj',100)
b.show_details()


#4queoops

class Employee:
    employee_count=101
    
    def __init__(self,name,des,sal):
        self.name=name
        self.des=des
        self.sal=sal
        self.eid='e'+ str(Employee.employee_count)
        Employee.employee_count+=1
    def show_details(self):
        print(self.name)
        print(self.des)
        print(self.sal)
        print(self.eid)
        
    @classmethod
    def total_employees(self):
        return cls.employee_count()-101
        

        
E=Employee('sneha','software engineer',1000000000)
E=Employee('sneha','software engineer',1000000000)

E.show_details()




