# mondrian-turtle-
#python
import turtle, random

t=turtle.Turtle()

t.shape("turtle")

for i in range(30):
    
    x=random.randint(-300,300)
    
    y=random.randint(-300,300)
    
    length=random.randint(10,300)
    
    a=random.random()
    
    b=random.random()
    
    c=random.random()
    
    t. up()
    
    t.goto(x,y)
    
    t.color(a,b,c)
    
    t.down()
    
    t.begin_fill()
    
    for j in range(4):
        
        t.forward(length)
        
        t. left(90)
        
    t.end_fill()       
   
