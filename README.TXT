Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

21. It starts at 00:00 because by default the values of hours and minutes are both zero.
23. 60 times 
24. NumberDisplay digit = new NumberDisplay(10);
25. Rectangle window = new Rectangle(5, 10);
26. It creates a ClockDisplay object with a starting time and you put the hours and minutes in the object. It then creates a NumberDisplay object for hours with a limit of 24 and another NumberDisplay object for minutes with a limit of 60.
27. The difference between them is one as a fixed start time and the other you can customize yourself. The similarities is that both have a NumberDisplay object for hours(24) and minutes(60).
28. The print method doesnt return anything because its void and the getStatus method returns int. 
29. The type of object created are: square, triangle and circle
30. roof.changeSize, roof.moveHorizontal, roof.moveVertical and roof.makeVisible
31. Yes, the internal method call draw()
32. 2
 
