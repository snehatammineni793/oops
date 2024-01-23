#ducktyping

def petlover(pet):
    pet.talk()
    pet.walk()

class duck:
    def talk(self):
        print("duck is talkig")
    def walk(self):
        print("duck is walking")
class dog:
    def talk(self):
        print("dog is talkig")
    def walk(self):
        print("dog is walking")
        
d=duck()
petlover(d)



