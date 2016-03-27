""" This program is a calculator for area. The program first prompts the user to select a shape. it then calculates the area of the shape depending on selection and prints that area to the user """

from math import pi
from time import sleep
from datetime import datetime

now = datetime.now()

print "Welcome human. Your area calculator is now warming up. Please give me a few seconds to get ready for computation"

print "Current time: %s/%s/%s %s:%s" % (now.month, now.day, now.year, now.hour, now.minute)

sleep(2)

print "Okay I am ready now"

hint = "Dont forget to include the correct units!"

option = raw_input("Please choose a shape. Enter C for Circle or T for Triangle: ")

option = option.upper()

if option == "C":
  radius = float(raw_input("Please enter the radius of your circle: "))
  area = pi * radius**2
  print "The pie is baking..."
  sleep(1)
  print ("Area: %.2f. /n%s" % (area, hint))

elif option == "T":
  base = float(raw_input("Please enter the base of the triangle: "))
  height = float(raw_input("Please enter the height of the triangle: "))
  area = (0.5) * base * height
  print "Uni Bi Trie..."
  sleep(1)
  print ("Area: %.2f. /n%s" % (area, hint))
  
else:
  print "Looks like you entered garbage the program will now exit... suck it monkey!"
	
  
  
