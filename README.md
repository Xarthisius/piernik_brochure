InSilicoLab for Astrophysics
============================

With the advent of PLGRID infrastructure Polish scientists have been equipped with a substantial computational
resources, forming favourable conditions for the development of all research areas relying on numerical simulation
techniques. However, modern hydrodynamical simulation codes require a properly configured software environment.
Installation of the compilers, libraries and postprocessing software requires technical know-how that is not common in
the population of young researchers and students of astronomy. To reduce the barriers inhibiting the start of the
newcomers to the field of computational astrophysics we have implemented a web-based workspace for astrophysical
simulation codes based on [InSilicoLab framework] [isl].

InSilicoLab for Astrophysics is a solution dedicated for computational astrophysicists intending to conduct a numerical
experiment using the PLGRID infrastructure. Currently, it serves as an interface for the multi-purpose,
magnetohydrodynamical, open-source software [PIERNIK] [piernik] -- an MHD code that relies on a dimensionally split,
second order algorithm in space and time, allowing to account for various fluid components: multiple fluids, dust,
cosmic rays, and additional physical processes, such as fluid interactions and Ohmic resistivity effects.

As a result, scientists using only a web browser can perform a full sequence of actions starting from copying of the
source code from a publicly accessible repository, through the remote compilation of the code, execution of the
numerical experiment in the PLGRID infrastructure and an immediate visualization of the results using the
[yt package] [yt]. Additionally the simulation results are stored as binary HDF5 files in LFC Catalogue, available for
further analysis. ISL for Astrophysics vastly softens the learning curve of advanced astrophysical simulations, bringing
new possibilities for scientists around the world.

![Snippet from InSilicoLab for Astrophysics](https://github.com/Xarthisius/piernik_brochure/raw/master/isl.png)


References
----------

[isl]: http://insilicolab.cyfronet.pl/ "http://insilicolab.cyfronet.pl/"
[piernik]: http://piernik.astri.umk.pl "http://piernik.astri.umk.pl"
[yt]: http://yt-project.org/ "http://yt-project.org/"
