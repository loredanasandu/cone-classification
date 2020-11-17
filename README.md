# Classification of convex cones
The program classifies the convex cone generated by input vectors  <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_1,&space;v_2,&space;...&space;,&space;v_n" title="v_1, v_2, ... , v_n" /> in the vector space  <img src="https://latex.codecogs.com/gif.latex?\inline&space;\mathbb{R}^3" title="\mathbb{R}^3" />. This was my final project of the module "Computational Tools for Mathematics" for the Bachelor's Degree in Mathematics at the Autonomous University of Barcelona.

## Theoretical classification of convex cones in <img src="https://latex.codecogs.com/gif.latex?\dpi{150}&space;\large&space;\mathbb{R}^3" title="\large \mathbb{R}^3" />
Let C be a convex cone in <img src="https://latex.codecogs.com/gif.latex?\inline&space;\mathbb{R}^3" title="\mathbb{R}^3" />, i.e. a subset <img src="https://latex.codecogs.com/gif.latex?C&space;\subset&space;\mathbb{R}^3" title="C \subset \mathbb{R}^3" /> that is closed under linear combinations with non-negative coefficients. C can be classified as follows:

 - **Cone {0}**, if <img src="https://latex.codecogs.com/gif.latex?C&space;=&space;\left&space;\{&space;0&space;\right&space;\}" title="C = \left \{ 0 \right \}" />
 - **Ray**, if  dim(<img src="https://latex.codecogs.com/gif.latex?C" title="C" />) = 1  and <img src="https://latex.codecogs.com/gif.latex?C" title="C" /> is generated by the conic combination of one vector.
 - **Line**, if dim(<img src="https://latex.codecogs.com/gif.latex?C" title="C" />) = 1 and <img src="https://latex.codecogs.com/gif.latex?C" title="C" /> is generated by two vectors.
 - **Plane angle**, a cone with the vertex at the origin of the space <img src="https://latex.codecogs.com/gif.latex?\inline&space;\mathbb{R}^3" title="\mathbb{R}^3" />, and generated by two vectors which form an angle <img src="https://latex.codecogs.com/gif.latex?\alpha" title="\alpha" /> such that 0 < <img src="https://latex.codecogs.com/gif.latex?\small&space;\left&space;|&space;\alpha&space;\right&space;|" title="\small \left | \alpha \right |" /> < <img src="https://latex.codecogs.com/gif.latex?\pi" title="\pi" />. An example is shown in figure 1:
 
<figure>
    <img src="./figures/plane_angle.png" width="350" title="Plane angle" alt="Plane angle">
    <figcaption>Fig. 1: A plane angle generated by vectors <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_1" title="v_1" /> and <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_2" title="v_2" />.</figcaption>
</figure>

 - **Half-plane**
 - **Plane**, i.e. <img src="https://latex.codecogs.com/gif.latex?C&space;=&space;\mathbb{R}^2" title="C = \mathbb{R}^2" />
 - **Polyhedral cone**, also called _solid angle_. An example is shown in figure 2:

<figure>
    <img src="./figures/polyhedral_cone.png" width="350" title="Polyhedral cone" alt="Polyhedral cone">
    <figcaption>Fig. 2: A polyhedral cone generated by vectors <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_1" title="v_1" />, <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_3" title="v_3" />, <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_5" title="v_5" />, <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_6" title="v_6" /> and <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_8" title="v_8" />.</figcaption>
</figure>

 - **Solid dihedral angle**, a cone with the shape of an infinite wedge. An example is shown in the following figure:

<figure>
    <img src="./figures/dihedral_angle.png" width="350" title="Dihedral angle" alt="Dihedral angle">
    <figcaption>Fig. 2: A solid dihedral angle generated by vectors <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_1" title="v_1" />, <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_2" title="v_2" />, <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_3" title="v_3" /> and <img src="https://latex.codecogs.com/gif.latex?\inline&space;v_4" title="v_4" />.</figcaption>
</figure>

 - **Half-space**
 - **Space**, i.e. <img src="https://latex.codecogs.com/gif.latex?C&space;=&space;\mathbb{R}^3" title="C = \mathbb{R}^3" />

 
***
Project in progress
