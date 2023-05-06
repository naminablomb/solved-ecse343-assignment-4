Download Link: https://assignmentchef.com/product/solved-ecse343-assignment-4
<br>



Question 1: <strong>Nonlinear Equations for univariate case.</strong>

<ol>

 <li>a) Bisection Method is used for tfinding the roots of a continuous function, , given endpoints;. The interval contains a root, , because  and          have opposite signs.</li>

</ol>

Bisection method bisects the given interval at the midpoint,          and then chooses a new interval based such that end of point of interval have opposite signs, i.e., if        , then the new interval is set to    then the interval is set to .

The above procedure is repeated until the following two conditions are simultaneously met,

The function value at the interval is sufficiently small, i.e.,

The new interval is sufficiently small, i.e.,

<u>Implement the Bisection Method in the cell below to find the root of              in the interval </u>. <strong>Show the number of iterations the bisection method took to converge.</strong>

Use the cell below to implement your code.

Note: There is no need to write the function for Bisection Method. However, if you wish to implement the function, use the appendix.

<u>Implement the <strong>Newton-Raphson</strong> Method in the cell below to find the root of </u>convergence is not reached in 100 iterations, quit the algorithm by displaying an error message indicating that Newton-Raphson failed to converge.

Show the number of iterations the Newton-Raphson method took to converge.

If the convergence is not reached for Newto-Raphson in 100 iterations, quit the function by displaying an error message indicating that Newton-Raphson failed to

Find a solution of the following system of three nonlinear equations using Newton-Raphson method. ,        where

<ol>

 <li>Write a MATLAB function named <em>evaluateEquations(x)</em>, that evaluates the above equation at a given input vector.</li>

</ol>

Use the framework of the function provided in the Appendix.

<ol>

 <li>Write a MATLAB function named <em>evaluateJacobian()</em>, that evaluates the Jacobian of the above equations.</li>

</ol>

Use the framework of the function provided in the Appendix.