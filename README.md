# org.polymc.PolyMC

A flatpak for [PolyMC](https://github.com/PolyMC/PolyMC)  
Please see upstream README for more information.

## FAQ

### How do I run MC on a Hybrid-GPU system with a dedicated nvidia GPU using PolyMC?

The flatpak includes a `prime-run` script, which when set as the wrapper command in instance settings, runs MC using the Nvidia GPU.  
Soon this should be unneccesary, as it has been fixed in the master branch of the launcher already.
