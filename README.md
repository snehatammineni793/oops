#1 queoops

from random import *

class Dice:
    def __init__(self,sides):
        self.sides=sides
        
    def roll_dice(self):
        print(randint(1,self.sides))
        

d=Dice(8)
d.roll_dice()

