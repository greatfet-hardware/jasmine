# Jasmine
a lithium polymer battery charging GreatFET neighbor

When operating a GreatFET under LiPo power from Jasmine, the voltage may drop under 3.3VDC.

The default charge rate for Jasmine is 15mA. The default can be reconfigured by populating R17 (FIXME).

Required KiCad dependency:

https://github.com/greatscottgadgets/gsg-kicad-lib

If you are using git, the preferred way to install gsg-kicad-lib is to use the
submodule:

```
git submodule init && git submodule update
```
