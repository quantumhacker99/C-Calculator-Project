This project takes input of an equation as a string. Then it returns the solution to the equation or returns that there is no answer if there is no solution. It operates on 9 tasks, which are:
Task 1: Linear equations in one variable called “x”.
Task 2: Linear equations in two variables called “x” and “y”, where the two equations are separated by
“;”.
Task 3: Linear equations in one variable called “x”, with values in left- and right-hand sides of the
equation.
Task 4: Quadratic equations in one variable called “x”, where solutions “exist” in our case only if the
discriminant is non-negative. The power operator is representing using the hat symbol “^”.
Task 5: Non-homogeneous linear system equations with three variables called “x”, “y”, “z”, which can
have cases of unique, or non-unique (i.e. no, and infinite) solutions. The equations are separated using
“;”.
Task 6: Trigonometric equation of the tangent form, with one variable called “x”, where the solution is in
radians. The equation format will be either “a*sin(x)=b*cos(x)” or “a*sin(x)-b*cos(x)=0”.
This is built in a hierarchical structure where each task is built on another. For example, task 3 is built on task 1 in which both sides of the equation are solved using code for task1.
