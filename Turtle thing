from turtle import *
import random, time, os, turtle
colors = ['aquamarine', 'cyan', 'plum', 'dark orchid', 'LimeGreen', 'goldenrod', 'DarkKhaki', 'DarkOrange', 'HotPink']
shape("turtle")
speed(10)
pencolor(random.choice(colors))
pensize(6)
Screen().bgcolor("white")
hideturtle()
def vform():
  right(25)
  forward(50)
  backward(50)
  left(50)
  forward(50)
  backward(50)
  right(25)
  pencolor(random.choice(colors))
def snöflingearm():
  for x in range(0,4):
    forward(30)
    vform()
  goto(0, 0)
def snöflinga():
  for x in range(0, 9):
    snöflingearm()
    right(40)
snöflinga()
pencolor("black")
turtle.write('A swedish "snöflinga".', font=("Times New Roman", 20, "normal"), align="center")
