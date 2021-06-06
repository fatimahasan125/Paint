# Paint
An application resembling Microsoft Paint using Object Oriented Programming in C++ and GP142 graphics

## How to run

Open Visual Studio and create a new empty Win32 Project (Make sure you don't create a Console Application) \
Next, add the header files and source files to your project \
Finally, build and run the PaintSource.cpp file


## How to use 

Below is a screenshot of what the default home page looks like \
The functionalities that you can perform from the GUI (from top to bottom) \
1. Draw Rectangle
2. Draw Circle
3. Draw straight line
4. Draw polygon
5. Draw connected lines
6. Erase something you drew originally
7. Write text
8. Save your drawing (it is saved to a file called drawing.pb)
9. Load a previous drawing (it is loaded from drawing.pb)
10. Fill a drawing with colour (which you can choose from the palette given at the top

![paint](https://github.com/fatimahasan125/Paint/blob/main/paint_screenshots/1.png?raw=true)

To draw a circle, choose the option from the left panel, then click on the screen twice. First click would be the center of the circle and second click would be where the circle is drawn (so the coordinates of second click - first click give the radius of the circle) 

Similarly, to draw a rectangle, choose the option from the panel and then click twice. First click refers to the top left corner of the rectangle and second click refers to the bottom right corner of the rectangle. 

To draw a polygon, click on the screen multiple times, each of which would become a corner of the polygon. Once you have clicked for all the corners, press any key on the keyboard and the polygon will be drawn. Same for connected lines. 

To draw a line, click any two points and they will be connected to create a line. 

To fill any shape, click on the last option from the panel, choose a colour from the top, and click inside the shape you wish to colour. 

To erase any shape, click on the eraser icon and then click inside the shape you wish to erase

An example of a drawing is shown below: 

![paint](https://github.com/fatimahasan125/Paint/blob/main/paint_screenshots/2.png?raw=true)
