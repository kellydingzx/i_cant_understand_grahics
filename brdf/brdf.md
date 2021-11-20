## BRDF: Bi-directional Reflectance Distribution Function

The reflectance property of a material in a scene.
https://www.youtube.com/watch?v=R9iZzaXUaK4

**Bi-direction:** 
- where the light comes from, illumination direction 
- where the light is been reflected and observed, reflection direction

<img src="brdf-1.png" width="400">

Represent the incoming ray and outgoing ray in terms of theta and phi.

<img src="brdf-2.png" width="400">

Irradiance: the amount of light energy from one thing hitting a square meter of another each second

<img src="brdf-3.png" width="400">

<img src="brdf-3-5.png" width="400">

Helmhortz property: 
- Flip the incoming ray and outgoing ray, still same property of BRDF
- Not exactly the same brightness seen from observer, just to say that the ability of the surface(material) is the same.

<img src="brdf-4.png" width="400">

Isotropic surface: 
- When the camera move around the surface, the brightness of the point we focus on remains the same.
- BRDF function only requires 3 inputs.

<img src="brdf-5.png" width="400">
