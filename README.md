# Game-with-Shapes
A function taking two inputs as square length and circle radius .If the circle is smaller than the aquare we can place circle inside the square otherwise not
def game(Radius,Length):
    if 2*Radius>Length:
        return "circle cannot be inside Square"
    else:
        return "circle can be inside Square"
Radius=int(input())
Length=int(input())
print(game(Radius,Length))
