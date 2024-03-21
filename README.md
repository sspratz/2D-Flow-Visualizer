# 2D-Flow-Visualizer
Visualization of point behavior for a pair of EOD equations.

Thanks to a course called Modelling of dynamical systems, I wanted to do a code to better visualize the effect of specific points in a 2D plane for a given set of equations:

$`\dot x = r*x - 3*x^{3} - y`$

$`\dot y = x - y`$

With r a parameter. Later on, the problem evolved into a more general one:

$`\dot x = r*x - 3*x^{3} - y`$

$`\dot y = \frac{1}{t} * (x - y)`$

Where there is another parameter t that "slows" or "swifts" the response.

So the code took some little twists and got more and more complex with the more parameters it could consider. 

Now it is actually pretty useful to play with, as it uses the package ipywidgets to visualize instant changes in some parameters.

Hope it helps anyone :D
