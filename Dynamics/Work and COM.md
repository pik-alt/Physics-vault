
**Work is the product of force and distance travelled in the direction of the force**

$W= \mathbf{F}\cdot \mathbf{x}$   For a straight line motion and constant force


If the line is straight but the force varies:

$W = \displaystyle\int_{x_{0}}^{x_{1}} \mathbf{F}(x) \, d\mathbf{x}$

If the force and the direction varies as you move along a path:

$W=\displaystyle\int_{r_{1}}^{r_{2}} \mathbf{F}\cdot \, d\mathbf{r}$

$W=\displaystyle\int_{r_{1}}^{r_{2}} F(\mathbf{r})\cos\theta(\mathbf{r}) \, dr$

---
## Work Energy Theorem

**The work done by the resultant force on a particle is equal to the change in the kinetic energy of the particle**

$W=\Delta E_{k}$

This means that if the speed of a particle remains constant, then no work has been done to it.

---

## Centre of Mass

**The centre of mass of a body, or a system of bodies, is the point that moves as though all the mass were concentrated at that point and all the external forces were applied there.**


For a system of particles:

$x_{cm} = \frac{m_{1}x_{1} + m_{2}x_{2}}{m_{1} + m_{2}}$

if we allow $M$ to be the total mass:

$Mx_{cm} = m_{1}x_{1} + m_{2}x_{2}$


If there's even more particles, you just sum the things all up.

$x_{cm} = \frac{1}{M}\displaystyle \sum_{i=1}^{n}m_{i}x_{i}$

In 3 dimensions, you can either find the centre of mass for all 3 dimensions separately or use vectors.

$\mathbf{r}_{cm} = \frac{1}{M}\displaystyle \sum_{i=1}^{n}m_{i}\mathbf{r}_{i}$


---

## Power

**Power is the rate of work**

 Using a neat derivation trick:

**Derivation:**
	$W=\mathbf{F}\cdot\Delta \mathbf{r}$
	$\frac{dW}{dt}=\mathbf{F}\cdot \frac{d\mathbf{r}}{dt}=\mathbf{F}\cdot \mathbf{v}$

We can get to  $P=\mathbf{F}\cdot \mathbf{v}$


---

## COM for Continuous bodies

To find the centre of mass in vector form, we do a similar thing as before

$\mathbf{r_{cm}} = \frac{1}{M}\displaystyle\int \mathbf{r}dm$

except this time its an integral and not a sum.

We can replace $dm$ with:

$dm=\rho(\mathbf{r})\times d^{3}\mathbf{r}$

Which is just mass = density times volume.
Plugging this back into the above formula, we get:

$\mathbf{r_{cm}}=\displaystyle\int_{V}^{} \mathbf{r}\rho(\mathbf{r})d^{3}\mathbf{r}$

where $V$ is the total volume

Note that this is a general case, where density is a function of position.


---

## External Forces

**We use the centre of mass because we can use it as the point on which all *external* forces act**

Using our above definition of the [[Work and COM#Centre of Mass|centre of mass]],  we can differentiate with respect to time twice and get:

$M\mathbf{a}_{cm} = \mathbf{F}_{1} + \mathbf{F}_{2} + \dots + \mathbf{F}_{n};$


All internal forces within a system of particles (such as the electrostatic attraction between atoms in a ball for example) must come in [[Newton's Laws|Newton Third Law pairs]], so they contribute nothing to the sum force.

If there's an additional force on one of the particles in the system, it must be an external force that survives all the summing of forces:

$M\mathbf{a}_{cm}=\displaystyle \sum_{i=1}^{n}\mathbf{F}_{i}=\mathbf{F}_{\text{external}}$


If there are no external forces, then all the internal forces cancel each other out and the sum above goes to 0.

---

## Kinetic energy of a system of particles

**The kinetic energy of a system of particles is the kinetic energy associated with the motion of the centre of mass.**

$K_{cm}=\frac{1}{2}Mv^{2}_{cm}$

If there are some straggler particles that move relative to the centre of mass, then you need to add their kinetic energy to the total one, with the velocity again being relative to the centre of mass.

$K=\frac{1}{2}Mv^{2}_{cm} + \displaystyle \sum_{i} \frac{1}{2}m_{i}u^{2}_{i}$

where $u_{i}$ is the relative velocity of the particle(s).

---

## Reduced Mass

If we're working with two particles, then it can be easier to work in terms of the centre of mass and the relative velocities of the particles:

$\mathbf{v}_{cm} =\text{ described above in}$ [[Work and COM#Centre of Mass|centre of mass]].

$\mathbf{v}_{relative}=\mathbf{v}_{1} - \mathbf{v}_{2}$

Through a derivation that I don't really understand, you can find that:

$K=\frac{1}{2}m_{1}v^{2}_{1} + \frac{1}{2}m_{2}v_{2}^{2} \newline = \frac{1}{2}Mv_{cm}^{2} + \frac{1}{2}\mu v_{\text{rel}}^{2}$

where $\mu$ is the **reduced mass**:

$\mu = \frac{m_{1}m_{2}}{m_{1} + m_{2}}$

