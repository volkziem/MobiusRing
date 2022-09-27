# MobiusRing
Here we describe the design of the racetrack-shaped Mobius ring from 

- V. Ziemann, *Beam parameters of a Mobius ring,* FREIA Report 2022/01, and [arXiv:2201.01083](https://arxiv.org/abs/2201.01083).
 
which is based on 90-degree FODO cells.  First we define the basic cell in the arcs and in the dispersion suppressor. Then we design the Mobius straight section to adjust the coupling and the straight section to adjust the tunes. Finally we assemble the ring, caluclate the beta functions and tunes, as well as the radiation integrals, based on the new method from 

- V. Ziemann, A. Streun, *Equilibrium parameters in coupled storage ring lattices and practical applications,* Physical Review Accelerators and Beams 25 (2022) 050703.

The contents of this repository
  - [Design of the Mobius ring](./MobiusRing.html): Matlab [live script](MobiusRing.mlx) and [pdf](MobiusRing.pdf).
  - Description of the [Beam optics support functions 5D](BeamOpticsSupportFunctions5D.html) and [pdf](BeamOpticsSupportFunctions5D.pdf).
  - The [zip file](BeamOpticsSupportFunctions5D.zip) with the subdirectory 5D that contains all Matlab support functions.
  - The MATLAB script **scan_the_coupling**, which sets the excitation of the skew quadrupoles between 0 and 1.5 times the value for the Mobius configuration. This routine might take anywhere between 5 and 15 minutes to complete.
  - The script **scan_the_coupling_display** to prepare the corresponding plots.

More MATLAB live scripts based on software from [Volker Ziemann, Hands-on Accelerator physics using MATLAB, CRCPress, 2019] 
(https://www.crcpress.com/9781138589940) are available at [MATLAB live scripts](https://ziemann.web.cern.ch/ziemann/mybooks/mlx).
