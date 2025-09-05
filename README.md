mport turtle as t
t.Screen()
tom=t.Turtle()
def up():
    tom.setheading(90)
    tom.forward(10)
def down():
    tom.setheading(270)
    tom.forward(10)
def left():
    tom.setheading(180)
    tom.forward(10)
def right():
    tom.setheading(0)
    tom.forward(10)
t.onkey(up,"Up")
t.onkey(down,"Down")
t.onkey(left,"Left")
t.onkey(right,"Right")
t.listen()
t.exitonclick()
