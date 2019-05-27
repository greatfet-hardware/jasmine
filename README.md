# Jasmine
a lithium polymer battery charging GreatFET neighbor

When operating a GreatFET under LiPo power from Jasmine, the voltage may drop under 3.3VDC.

The 10k resistors on R2 configures the charge current to be 100mA which is the fastest supported charge rate for many LiPo batteries. The charge rate can be reconfigured changing the R2 resistor or adding a resistor to R3.

Required KiCad dependency:

https://github.com/greatscottgadgets/gsg-kicad-lib

If you are using git, the preferred way to install gsg-kicad-lib is to use the
submodule:

```
git submodule init && git submodule update
```
