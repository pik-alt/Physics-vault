(These are polar vectors in cartesian co-ordinates, for polar co-ordinated see [[Polar Co-ordinates]])
$(x,y) \to (r,\theta)$, they both express $\underline{r}$

$\underline{r} = r(\cos(\theta)\hat{\underline{i}} + \sin(\theta)\hat{\underline{j}})$

$r$ is the polar co-ordinate magnitude of the vector.


$\hat{\underline{r}} \text{ and } \hat{\underline{\theta}} \text{ are always perpendicular.}$

$\hat{\underline{r}} \text{ always points in the direction of } \underline{r}$
$\hat{\underline{\theta}} \text{ points in the direction of positive } \theta$



$\underline{\hat{r}} = \frac{\underline{r}}{r}$,      $\hat{\underline{\theta}} = -\sin(\theta)\hat{\underline{i}} + \cos(\theta)\hat{\underline{j}}$

$\hat{\underline{r}} = \cos(\theta)\hat{\underline{i}} + \sin(\theta)\hat{\underline{j}}$

We can then see that:
$\frac{d}{d\theta}\hat{\underline{r}} = \hat{\underline{\theta}}$


$\hat{\underline{\theta}} \text{ and } \hat{\underline{r}}\text{ are not the same everywhere, and they only depend on the position, not the relative motion}$

---

$\underline{v} = \frac{d\underline{r}}{dt} = \frac{d}{dt}r\underline{\hat{r}}$

=

$\frac{d}{dt}r \cdot \hat{\underline{r}} + \frac{d}{dt}\hat{\underline{r}} \cdot r = \dot{r} \hat{\underline{r}} + r \cdot\left( \frac{d}{d\theta} \hat{\underline{r}}\right)\cdot \frac{d\theta}{dt}$ 



### N.B.
$\hat{\underline{r}} = \hat{\underline{r}}(\theta)$

$\frac{d}{dt}\hat{\underline{r}}(\theta) = \dot{\theta} \hat{\underline{\theta}} \text{ by the chain rule}$




**$\underline{v} = \dot{r} \hat{\underline{r}} + r \dot{\theta} \hat{\underline{\theta}}$**

---

$\underline{a} = \frac{d\underline{v}}{dt}$

$\left( \frac{d}{dt} \dot{r}\right)\hat{\underline{r}} +\left( \frac{d}{dt}\hat{\underline{r}} \right)\dot{r} + \left( \frac{d}{dt}r \right)\dot{\theta}\hat{\underline{\theta}} + \left( \frac{d}{dt}\dot{\theta} \right)r \hat{\underline{\theta}} + \left( \frac{d}{dt}\hat{\underline{\theta}} \right)r \dot{\theta}$

(a bunch of re-arrangement later)

$\underline{a} = (\ddot{r} -r \ddot{\theta})\hat{\underline{r}} + (2\dot{r}\ddot{\theta} +r \ddot{\theta})\hat{\underline{\theta}}$


---
### Changing frames of reference to help solve dynamics problems

If you are looking at two or more particles that are moving with relation to the ground or stationary frame, you can often simplify the problem by looking at the reference frame to one of the particles.

You do this by realising that the particle in its own frame of reference is stationary, so it (and so everything else in the system) must be given a velocity vector equal and opposite to the velocity of the particle in question.






 






