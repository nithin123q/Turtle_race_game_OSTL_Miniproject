# Turtle Race (small fun game)

### Aim: Write a program in python to implement a turtle race game(a single player game)

### REPORT:
Description: Use loops to draw a race track and create a racing turtle game.
What you will make?
This project introduces for loops through a fun turtle race game. Loops are used to draw 
the race track and to make the turtles move a random number of steps each turn. If you 
have a group of people to play the game, each person picks a turtle and the one that gets 
the furthest is the winner.

First we will import turtle ,where the point is there on the turtle. All properties are 
imported in the turtle. “Random import randint” is used because we require random integer. 
When “time sleep” is used the turtle will stop for require time.
Now penup and pendown function was used:
Penup is used to make a line whereas pendown will not make a line.

For example:
pendown()
right(90)      :This moves the object to the right of 90 degree.   
Pendown(0,0)   :It will not make a line,but will place it to the origin.
“for step in range” is used to make track.
Forward and backward is used for directions.

Given part in the program:
For example:
t1=Turtle()
t1.color('coral')
t1.shape('turtle')            //The turtle will start moving as directed//
t1.penup()
t1.goto(0,-15)
t1.pendown()

.
For the track:
for x in range(6):
    right(90)
    penup()
    forward(30)                   //it will start making the five horizontal lines//
    left(90)
    backward(320)
    pendown()
    forward(320)


for x in range(18): 
        pendown()
        backward(5)
        penup()                         //it will start making the vertical lines//
        backward(5)
        penup()
        left(90)
        forward(20)
        speed(0)



 
 RULES OF THE GAME: 
1.Start of the game
The players decide or challenge their friends by predicting their winning turtle.

2.Speed of the Turtle
The speed of the turtle is taken randomly by the program.

3.End of the game
The turtle with the fastest among them wins the race (1st,2nd and 3rd position) followed by the player that predicted their turtle.

### Requirement of the project:

•	Python IDLE version 3.6 or 3.7



