# Game-with-Shapes
def game(Radius,Length):
    if 2*Radius>Length:
        return "circle cannot be inside Square"
    else:
        return "circle can be inside Square"
Radius=int(input())
Length=int(input())
print(game(Radius,Length))
