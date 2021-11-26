# star_with_random_color_sides
import turtle
import random
riley=turtle.Turtle()
riley.width(10)
               
def mood_star():
    for side in range(5):
        color = ["yellow","lightblue","grey","red","magenta"]
        now = random.choice(color)
        riley.color(now)
        riley.forward(100)
        riley.left(144)

mood_star()
