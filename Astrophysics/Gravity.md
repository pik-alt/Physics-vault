5/10/26

Gravitational force is defined by:
$F=G\left( \frac{mM}{r^2} \right)$

$G$ is the gravitational constant defined as $6.67\times 10^-11\text{m}^3\text{Kg}^1\text{s}^-2$

local small acceleration due to gravity is $9.81\text{m}\text{s}^-1$


From $F=ma$, we can get

$mg=G\left( \frac{mM}{r^2} \right)$
$g= \frac{GM}{r^2}$


To derive a formula for velocity and position, we can integrate:

$g=\frac{dv}{dt}$

$\int_{0}^tg\ dt=\int_{0}^vdv$

$gt=v=\frac{ds}{dt}$

$\int_{0}^tgt\ dt=\int_{0}^sds$

$\frac{1}{2}gt^2=s$

$t=\sqrt{ \frac{2s}{g} }$

$v=gt$

$\therefore$

$v=g\sqrt{ \frac{2s}{g} } = \sqrt{ 2gs }$



## Energy

When something doesn't start from a stationary velocity, you need to add the masses together rather than adding $v_{0}$ and $v_{1}$ to the kinetic energy formula.


$E=mgh$ only works for constant $g$, which is a good approximation very close to the Earths surface but get's worse and worse as you go higher up.

A better way to calculate it is to again take the integral.


$W=Fs = \int F\ ds = \int_{R_{E}}^{R_{E}+s}\ G\left( \frac{mM}{R^2} \right)\ dR$

$\int_{R_{E}}^{R_{E}+s}GmMR^-2\ dR$

$[-GmMR^-1]_{R_{E}}^{R_{E}+s}$

$GmM\times\left( \frac{1}{R_{E}} -\frac{1}{R_{E}+s}\right)$


## Escape velocity

To find an escape velocity, we can instead consider an object falling from infinity to the Earth, as the difference in energy between that and flying to infinity would be identical.

We showed above the formula for the energy, so if we input $\infty$ for $s$, we can see that

$\frac{1}{R_{E}+s} \to 0$

so the energy is just:

$\frac{GmM}{R_{E}}$

Which we can equate to the kinetic energy to find the velocity needed.

$\frac{1}{2}mv^2 = \frac{GmM}{R_{E}}$

$v_{\text{escape}}=\sqrt{ \frac{2GM_{E}}{R_{E}} }$

## Orbits

For an object to maintain a stable orbit,

$F_{\text{gravity}} = F_{\text{centripetal}}$

$\frac{GmM}{r^2} = \frac{mv^2}{r}$

doing some cancelling and re-arranging gets us to:

$v_{\text{orbital}} = \sqrt{ \frac{GM}{r} }$

which we can also write as $v_{\text{orb}} = \sqrt{ 2 }\times v_{\text{esc}}$








