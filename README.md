InSilicoLab for Astrophysics
============================

With the advent of PLGRID infrastructure Polish scientists have been equipped
with a substantial computational resources, forming favourable conditions for
the development of all research areas relying on numerical simulation
techniques. However, modern hydrodynamical simulation codes require a properly
configured software environment. Installation of the compilers, libraries and
postprocessing software requires technical know-how that is not common in the
population of young researchers and students of astronomy. To reduce the
barriers inhibiting the start of the newcomers to the field of computational
astrophysics we have implemented a web-based workspace for astrophysical
simulation codes based on InSilicoLab framework[1].

InSilicoLab for Astrophysics is a solution dedicated for computational
astrophysicists intending to conduct a numerical experiment using the PLGRID
infrastructure. Currently, it serves as an interface for the multi-purpose,
magnetohydrodynamical, open-source software PIERNIK [2,3] -- an MHD
code that relies on a dimensionally split, second order algorithm in space and
time, allowing to account for various fluid components: multiple fluids,
dust, cosmic rays, and additional physical processes, such as fluid
interactions and Ohmic resistivity effects.

As a result, scientists using only a web browser can perform a full sequence of
actions starting from copying of the source code from a publicly accessible
repository, through the remote compilation of the code, execution of the
numerical experiment in the PLGRID infrastructure and an immediate
visualization of the results using the yt package[4]. Additionally the
simulation results are stored as binary HDF5 files in LFC Catalogue, available
for further analysis. It is a vast improvement in 


References

[1] http://insilicolab.cyfronet.pl/
[2] Hanasz, M., Kowalik, K., Wóltański, D., & Pawłaszek, R. 2010, in EAS Publications Series, Vol. 42, EAS Publications Series, ed. K.
Goz´dziewski, A. Niedzielski, & J. Schneider, 275–280
[3] http://piernik.astri.umk.pl
[4] http://yt-project.org/
