# swarm-deferred
Automatically exported from code.google.com/p/swarm-deferred

This project uses a deferred lighting approach that can be implemented parallelly to the forward renderer in the Alien Swarm SDK.

All important source files can be found in src/materialsystem/ and the respective deferred/ directories in client/, server/ and shared/. Make sure to read the readme in src/ which contains further installation information.

Features
The deferred rendering pipeline currently implements the following:

cascaded shadow mapping with an atlas
dual paraboloid shadow mapping
perspective shadow maps
different kinds of PCF (color, depth-stencil)
cookies via textures
cookies via VGUI panels
light scattering via light volumes
Lights can be directly loaded from and written to VMF files opposed to placing them in Hammer only.
