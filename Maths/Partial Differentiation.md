
If you have a function with multiple variables, such as:

$u=x^2 + y^2$

You can get the gradient for either the x or y direction, which are different.

The notation is:

$\frac{\partial u}{\partial x} |_{y}$ which means "Differentiate in terms of x, hold the y"

so $\frac{\partial u}{\partial x} = 2x$


## Double differentiation

$\frac{\partial^2f}{\partial x \partial y} =$ take the $\frac{\partial f}{\partial x}$ and differentiate partially in terms of y.

$\frac{\partial^2 f}{\partial x \partial y} = \frac{\partial^2f}{\partial y\partial x}$ so you can do it in any order.


You can also do normal double differentiation $\frac{\partial^2f}{\partial x^2}$

## Relationship to full differentiation

$\delta z = \frac{\partial z}{\partial x}\delta x + \frac{\partial z}{\partial y}\delta y$
And then you take the limit in terms of both x and y to 0, divide through by what you need to get $\frac{dz}{dx} \text{or} \frac{dz}{dy}$


You can also do this to get shit in terms of $\frac{dx}{dt}$ or anything.


## Stationary Points

Same as normal, you can find a stationary point for a variable by equating it to 0:

$\frac{\partial f}{\partial x} = 0$


However, unlike in normal maths, this point can either be a maximum, minimum or a saddle point.


![[Saddle point.png]]

You can find out which one it is using this formula:

$\Delta = \left( \frac{\partial^2f}{\partial x\partial y} \right)^2 - \frac{\partial^2 f}{\partial x^2} \times \frac{\partial^2 f}{\partial y^2}$


- If $\Delta > 0,$ then it is a saddle point.
- If $\Delta < 0 \text{ and } \frac{\partial^2f}{\partial x^2} < 0,$ it's a maximum
- Else: minimum



