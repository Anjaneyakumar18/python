Define a class named Rectangle which can be constructed by a length and width. The Rectangle class has a method which can compute the area.

class Rectangle():
    def __init__(self,l,w):
        self.length = l
        self.width = w

    def area(self):
        return self.length*self.width


rect = Rectangle(2,4)
print(rect.area())
6:48 AM 29-Apr-23