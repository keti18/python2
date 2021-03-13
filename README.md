# python2
class Rectangle:

    width = 15
    height = 10

    def area(self):
        return self.width * self.height
    def perimeter(self):
        return self.width + self.height
rect1 = Rectangle()
print(rect1.width)
print(rect1.height)
print(rect1.area())
print(rect1.perimeter())
