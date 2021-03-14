#python 2nd სsemester
class Rectangle:
    def __init__(self, width=30, height=10):

        self.width = width
        self.height = height
    def area(self):
        return self.width * self.height

    def perimeter(self):
        return self.width * 2 + self.height * 2

rect1 = Rectangle()
print(rect1.width)
print(rect1.height)
print(rect1.area())
print(rect1.perimeter())

