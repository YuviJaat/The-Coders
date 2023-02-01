class Shape:
    def _init_(self, area, color):
        self.area = area
        self.color = color

class Rect(Shape):
    def _init_(self, area, color):
        super()._init_(area, color)

    def areaFunc(self):
        print("Area: ", self.area)

    def colorFunc(self):
        print("Area: ", self.color)

class Square(Shape):
    def _init_(self, area, color):
        super()._init_(area, color)

    def areaFunc(self):
        print("Area: ", self.area)
        
    def colorFunc(self):
        print("Area: ", self.color)

s1 = Rect(20, 'Blue')
s2 = Square(30, 'Red')

s1.areaFunc()
s1.colorFunc()
s2.areaFunc()
s2.colorFunc()