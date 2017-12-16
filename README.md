# Graphics Pipeline(Unity)
__________________________________________________________________________________________________________________________


## Application Phase ------------> Geometry Phase --------------> Rasterisation Phase


1. Application: This runs on CPU. It includes all the processes that occur in software like moving objects, collisions.
2. Geometry: How the virtual world is situated with respect to player. It involves calcuation about camerar like rotation, transformation & scaling of the world.
Rasterisation: Processing the env multiple times. Adding filters 

## A close look at Geometry & Rasterisation process:

Geometry -----> Illumination ------> Viewing Perspective -------> Clipping --------> Screen Space Projection -------> Rasterisation ---------> Display
  
1) Geometry: 

2) Illumination: This is where models are colored in lit.

3) Viewing Perspective: How camera is placed. Is the view perspective or orthographic? Field of view details

4) Clipping: To remove any details outside of camera's viewing angles

5) Screen Space Projection: A projection of 3D object on 2D space

6) Rasterisation: Filters


## Shaders in Unity

Shaders in Unity are written in ShaderLab. ShaderLab consists of 3 Parts 

Properties(Unity's part) ----------> SubShader(For Processing) ----------> Fallback(For Inferior GPUs)