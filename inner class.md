class customer:
    def __init__(self,id,name,bpin,spin):
        self.id=id
        self.name=name
        self.baddr=self.address(bpin)
        self.saddr=self.address(spin)
    
    
    class address:
        def __init__(self,pin):
            self.pin=pin
        
        def display(self):
            print(self.pin)
            
c1=customer(1,'sneha',532001,543211)
c1.baddr.display()
c1.saddr.display()
