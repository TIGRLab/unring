unring
------

Tool for removal of the Gibbs ringing artefact.

Based on the algorithm in the publication (please cite):

Kellner, E, Dhital B., Kiselev VG and Reisert, M.
Gibbs‐ringing artifact removal based on local subvoxel‐shifts.
Magnetic resonance in medicine, 76(5), 1574-1581.

**Setup**

Add `unring.py` to you `PATH`.

Depends on MATLAB: contains a compiled matlab implementation for working with nrrd files.

Compatible with 64 bit Linux due to reliance on compiled code. Touch base if you want source code for other systems.

Tested on Ubuntu 16.04, python 2.7, MATLAB R2014a.

