#Radiation  

When electrons are accelerated through a potential V and strike metal structures in the chamber (grid, inner walls, feedthroughs), a fraction of the electrical input power is converted to bremsstrahlung X-rays. A standard first-order estimate for the bremsstrahlung efficiency in a thick target is [10]:

$η≈9×10^{-10}Z_{eff}V$

with V in volts and Zeff an effective atomic number of the target material. For stainless steel, a conservative approximation is Zeff26.

The electrical power delivered to the discharge is:

$P_{e}=VI$

So the total bremsstrahlung X-ray power at 100kV is:

$P_{x} =ηP_{e}=(910-10Z_{eff}V)(VI)$

$η≈9×10-10^{(26)}(100000)=2.34×10^{{-3}}$

$P_{e}=(2.34×10^{-3})(1000)=2.34W$

Approximately 2W of X-ray power inside the chamber. Intensity is calculated as follows:

$I=P_{x}4πr^{2}$

$I=\frac{2.34}{12.57}=1.86×10^{-1} Wm^{-2}$

Assuming wall thickness of 3mm with $\rho=8.0 gcm^{-3}$ and a narrow-beam transmission type:

$T(E)=e^{\mu (E)x}, \mu(E)=\left( \frac{\mu}{\rho} \right)_{wall}(E)$

Using NIST table [9] at 100keV (E=0.10MeV):

$μ/ρ≈0.3717cm^{2}g^{-1}$

So:

$=(0.3717)(8.0)=2.97cm-1, T=e^{-(2.97)(0.3)}=4.10*10^{-1}$

Transmitted energy rate:

$=(1.86*10^{-1})(4.10*10^{-1})=7.63*10^{-2}Wm^{-2}$

From NIST for air transmittance at 100keV [11]:

$μ/ρ≈2.325*10^{-2} cm^{2}g^{-1}$

$H=(7.63*10^{-2})(2.325*10^{-2} )=1.77*10^{-4}Sv s-1$

$H=(1.77*10^{-4})(3600)=0.639Sv/ h$

The energy of an electron follows 

$$
E = eV = (1.6*10^{-19})*10^{5}=1.6*10^{-14}J
$$

This places a harsh upper limit on $X-Ray$ energy and thus frequency.

$$
f_{max} = \frac{E_{in}}{h}= \frac{1.6*10^{{-14}}}{6.62*10^{{-34}}} = 2.42*10^{19}Hz
$$

In reality a lower accelerating voltage (~$70keV$) and factoring in bremsstrahlung efficiency would yield much lower average electron energy, with a continuous spectrum up to $f_{max}$, but this upper limit on frequency and power does place a required detection bound for the $X-Ray$ detector.

|     |           |           |           |           |           |           |           |           |
| --- | --------- | --------- | --------- | --------- | --------- | --------- | --------- | --------- |
|     | 1.000E-01 | 5.027E-03 | 1.463E-01 | 2.132E-03 | 0.000E+00 | 0.000E+00 | 1.534E-01 | 1.484E-01 |

$\frac{\mu}{g}=0.148$

Intensity from

$$
I = I_{0}e^{-(\mu/\rho)(\rho t)}=7.63*10^{-2} e^{-0.148*1.225*2}= 0.053094
$$

$$
F = 0.00105
$$

$$
E_{flux}=0.00105*1.6*10^{-14}=1.68*10^{-17}
$$

# Detector Sizing

https://www.amptek.com/products/x-ray-detectors/cdte-x-ray-and-gamma-ray-detectors/cdte-x-ray-and-gamma-ray-detector

