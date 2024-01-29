from classes import Rectangle, Square, Circle

# создаем два прямоугольника

rect_1 = Rectangle(3,4)
rect_2 = Rectangle(12,5)

# вывод площади двух прямоугольников

print(rect_1.get_area())
print(rect_2.get_area())

square_1 = Square(5)
square_2 = Square(10)

# вывод площади квадрата

print(square_1.get_area_square(),
      square_2.get_area_square())

circle_1 = Circle(3)
circle_2 = Circle(6)

# вывод площади круга

print(circle_1.get_area_circle(),
      circle_2.get_area_circle())


figures = [rect_1, rect_2, square_1, square_2, circle_1, circle_2]
for figure in figures:
      if isinstance(figure, Square):
            print('Площадь квадрата равна ', figure.get_area_square())
      elif isinstance(figure, Rectangle):
            print('Площадь прямоугольника равна ', figure.get_area())

      else:
            print('Площадь круга равна ', figure.get_area_circle())
