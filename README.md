# The full plot

We should, in theory, be able to create an entire *parametric* modelling piece of software with
the associated simulation tools for fluids and geometry deformation. All this is then involves both the actual spline math, the
mesh tessellation, and then Monte Carlo methods.

Therefore, we really want to make up a set of CAD elements, *discrete differential geometry* (DDG) tools,
and finally, Monte Carlo geometry processing. This will take time, especially from scratch, but it
will certainly be worth it, I can't fucking *stand* FEM meshing anymore, and God knows I have been postponing
this task since I have been 11 years old.

## CAD tools

These will be the longest to complete in the list, but I just need certain capacities; spline
generation and boundary blending so that I'm minimally informed on how to do it.

## DDG toolset

This one is the most interesting. I want to perform geometric calculus at a high level,
computationally; staring down into scalar vorticitiy diagrams or using ParaView/Blender for the
simplest tasks is nothing but suffering.

## Monte Carlo Geometry Processing

I'll implement the shit out of *Walk On Spheres* on every differential operator that exists
if it means I will never have to catch a cell growth problem in a aerodynamics mesh ever again;
if it requires functional analysis and abstract multilinear algebra, so be it, it must be easier
than spending 6h making a tessellation that doesn't work FUCK I HATE FEM
