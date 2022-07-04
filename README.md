import turtle, random

t=turtle.Turtle()

t.shape("turtle")

t. color("yellow")

t.begin_fill() 

for j in range (30):

    x=random.randint(-300,300)

    y=random.randint(-300,300)

    len=random.randint(50,150)

    a=random.random()

    b=random.random()

    c=random.random()

    t.color(a,b,c)

    t.up()

    t.goto(x,y)

    t.down()

    t.begin_fill()

    for i in range(5):
        

        t.forward(len)

        t.left(144)

    t.end_fill()


