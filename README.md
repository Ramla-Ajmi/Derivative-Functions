Derivative Functions : 
     This Python project demonstrates how to compute and approximate the derivative of mathematical functions using the limit definition. The code evaluates the derivative at different points and compares the true derivative with approximations as the step size (h) changes.
     Idea Behind the Code
     The main idea of this project is to illustrate how we can use the limit definition of a derivative to approximate the derivative of a function. The code works as follows:
     Functions : We work with different mathematical functions, such as:
    	- f1(x) = sin(x)
    	- f2(x) = x⁴
    	- f3(x) = x² * log(x)
Limit Definition: The derivative of a function at a point x is approximated using the limit definition:
                                                         f^' (x)≈(f(x+h)-f(x))/h
     As the value of h gets smaller, the approximation becomes more accurate.
Graphical Visualization: 
     The code not only computes these approximations but also plots them, showing how the approximation converges to the true derivative by adjusting the step size (h).
Features : 
	 Compute derivatives: Approximates derivatives of the functions using different values for h (the step size).
	Plot true vs approximated derivatives: Visualize how well the approximation matches the true derivative by comparing graphs for different h values.
Requirements :
	  - Python 3
	  - Numpy
	  - Matplotlib

