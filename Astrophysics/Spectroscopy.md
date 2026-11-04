
**Interferometry is the combining of telescopes from different locations to act as one whole big dish.**

Collecting Area: $N \frac{\pi D^2}{4}, \text{ where }N\text{ is the number of telescopes}$
(most telescopes have the same diameter if used for interferometry)

Resolution: $\theta = \frac{\lambda}{d}, \text{ where }d\text{ is the largest distance between any two dishes}$


When getting data from telescopes, you can either focus on a particular wavelength/range of wavelengths, or look at the spectrum as a whole.

- Images: Use filters to observe a particular range of wavelength. With this you can get the position, shape or structure of the object
- Spectrum: Get intensity as a function of wavelength, get energy and temperature of the object


## Spectroscopy for real

To separate the individual wavelengths within a beam of light, you can either use a prism or diffraction grating.

Prisms work via refraction:

The refractive index of a material, n, is the ratio of the speed of light in a vacuum to the speed of light in that material:
 
 $n=\frac{c}{v}$
 Doing some more work, we can derive **Snell's law:**
$\frac{n_{2}}{n_{1}} = \frac{\sin\theta_{1}}{\sin\theta_{2}}$

Refraction angle depends on wavelength (as the refractive index depends on wavelength), which means that different coloured light bend differently upon entering a prism and so you can split them apart.


Diffraction Gratings work by generating local maxima and minima.

If you want positive interference between the two waves, you need the difference in length between them to be an integer number of wavelengths:

$\Delta l = n\lambda$

$\implies d\sin\theta = n\lambda$

$\text{ where d is the distance between slits and n is the nth maxima}$

because the diffraction depends on wavelength, you can split light into its constituent wavelengths because they have different maxima and minima.


### Detectors

Once you split the light, you still need a way to detect it.

CCD (Charge Crystal Detector's): Photons hit a sensor, release an electron via the photoelectric effect, which means that each pixel in the camera sensor is a detector.

Factors affecting detectors:
- Quantum Efficiency: Number of electrons that should be observed vs. how many actually are.
- CCD charge transfer efficiency: Fraction of electrons transferred during the read out (around 0.9999)
- Dynamic range: Highest number of electrons that can be counted
