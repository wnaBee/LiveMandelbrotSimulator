# LiveMandelbrotSimulator
An implementation for the exploration of the mandelbrot set to a depth of 2^53 - 1 in javascript

### use
Scroll function on mouse zooms the set in/out.\
The cursor on the set indicates where it will zoom.\
Click besides the circle to move set in corresponding direction.\
The greater the distance from the cursor, the larger the movement.

### mandelbrotprojCSS.html
Full version of mandelbrot simulator
function | type | Description
-------- | ---- | -----------
Set-Red | Slider | Determines the amount of red within the set
Set-Green | Slider | Determines the amount of green within the set
Set-Blue | Slider | Determines the amount of blue within the set
Red | Slider | Determines the amount of red outside the set
Green | Slider | Determines the amount of green outside the set
Blue | Slider | Determines the amount of blue outside the set
Iter | Slider | Determines the number of iterations preformed when encountering the set; lower values = better preformance \| higher values = better accuracy
Sens | Slider | Determines scroll sensitivity
Main Colour | Buttons | Decides the main colour outside the set
Secn Colour | Buttons | Decides the secondary colour outside the set
Tert Colour | Buttons | Decides the tertiary colour outside the set
Cursor | Button | hides the zoom cursor

### mandelbrot.html
Simplified version of `mandelbrotprojCSS.html` with better preformance, lacks GUI and requires source editing to change settings.
