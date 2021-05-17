# minetracer
A stub showing demo images and info regarding my CS488 raytracer

The full documentation regarding the process can be found [here](./report/project.pdf)

The following is a demonstration of the features implemented as part of this raytracer

## Specular Reflection
Specular reflection was implemented with Fresnel Reflectance applied to it.
![No specular reflection](specular_reflection_none.png)
![Specular reflection enabled](specular_reflection.png)

## Specular Transmission
Specular transmission was implemented with Fresnel Reflectance applied to it. Index of refraction
controls angle of refraction based on Snell's Law. From top to bottom index = 1.0, 1.3, 1.6
![Index=1.0](specular_transmission_1.0.png)
![Index=1.3](specular_transmission_1.3.png)
![Index=1.6](specular_transmission_1.6.png)

## Texture Mapping
Texture mapping was implemented and used for spheres, cubes and meshes
![Textures](texture_test.png)

## Bump Mapping
Similarly to texture mapping, bump mapping was implemented for spheres, cubes and meshes
![Bumps from the left](bump_test_left.png)
![Bumps from the right](bump_test_right.png)

## Depth of Field
Depth of field was implemented and is controlled by aperture size, focal length, and lens distance.
From top to bottom are 3 images with 300 focal length, 60 lens distance and
0.5, 2, 3 aperture length respectively.
![0.5 Aperture](depth_of_field_less.png)
![2 Aperture](depth_of_field.png)
![3 Aperture](depth_of_field_more.png)

## Photon Map - Mapping
Photons can be shot throughout the scene and rendered where they are saved
![Caustic Map](caustics-map.png)

## Photon Map - Gather
Caustic related photons can be gathered and added to light intensities. 
The first image is without caustics rendered, the second is with caustics.
![No caustics](caustics-none.png)
![With caustics](caustics.png)

## Environment Mapping
Skyboxes can be assigned. If no skybox exists, use gradient colour. Below is
a image without a skybox and two with different skyboxes. (The white sports are part of the texture)
![No skybox](skybox_test_no_sky.png)
![Skybox 1](skybox_test_front.png)
![Skybox 2](skybox_test_back.png)

## Modelling
Cone and Cylinder were implemented as extra primitives. A ingot, pickaxe
and potion bottom were hand modelled in Blender as well. (See final scene for custom models)
![Cone and cylinder](extra_primitives.png)

## Phong Shading
Phong shading can be toggled on to smooth normals of imported meshes
![No phong](potion.png)
![With phong](potion-phong.png)

## Final Scene
![Front door](minecraft_outside_dark.png)
![Inside](minecraft_inside_dark.png)
