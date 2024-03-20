# 2D-Flow-Visualizer
Visualization of point behavior for a pair of EOD equations.

Thanks to a course called Modelling of dynamical systems, I wanted to do a code to better visualize the effect of specific points in a 2D plane for a given set of equations:

$`\dot x = r*x - 3*x^{3} - y`$

$`\dot y = x - y`$

With r a parameter. Later on, the problem evolved into a more general one:

$`\dot x = r*x - 3*x^{3} - y`$

$`\dot y = \frac{1}{t} * (x - y)`$

So the code took some little twists and now it is actually pretty useful to play with, as it uses the package ipywidgets to visualize instant changes in some parameters.

Hope it helps anyone :D
