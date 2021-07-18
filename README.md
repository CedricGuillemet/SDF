# Signed Distance Field (SDF)

Resources, links, papers, discussions, ShaderToys on SDF and related algorithm.
Please contibute to this resource by sending your PRs!

## Tutorials / introductions

Jamie Wong, Ray Marching and Signed Distance Functions
http://jamie-wong.com/2016/07/15/ray-marching-signed-distance-functions/

Alex Benton, Ray Marching and Signed Distance Fields
http://bentonian.com/Lectures/FGraphics1819/1.%20Ray%20Marching%20and%20Signed%20Distance%20Fields.pdf

Sungiant, Sphere tracing signed distance functions (Scala)
https://github.com/sungiant/sdf

Rendering Worlds with Two Triangles / with raytracing on the GPU in 4096 bytes
https://www.iquilezles.org/www/material/nvscene2008/rwwtt.pdf

Raymarching Beginners' Thread
https://www.pouet.net/topic.php?which=7920&page=1

## Games and tools

### Dreams

Alex Evans at Umbra Ignite 2015: Learning From Failure
Dreams tech from early prototypes to cloud point rendering

https://www.youtube.com/watch?v=u9KNtnCZDMI

PDF: https://www.mediamolecule.com/blog/article/siggraph_2015

Dreams: Under the Hood with Alex Evans! 
https://www.youtube.com/watch?v=1Gce4l5orts

Alex Evans (NVIDIA), Optimising for Artist Happiness
https://www.youtube.com/watch?v=eGfX1iWzkh0&t=1273s

### MagicaCSG

Distance field editor with the same UI as MagicaVoxel by Epthtracy
https://ephtracy.github.io/index.html?page=magicacsg

### https://slimery.art/

SDF editor on the web 
https://slimery.art/
GIF here : https://twitter.com/DaniGatunes/status/1413388975713173506

### Distance Filed Modeler for Unreal Engine

https://twitter.com/SDFmodelerUE4


### Clayxels

Clayxels is the volumetric toolkit for Unity
https://assetstore.unity.com/packages/tools/game-toolkits/clayxels-165312

## Demos

SDF / Ray Marching Prototypes. A collection of SDF related examples using fungi to handle the rendering.
https://sketchpunk.bitbucket.io/

## Algorithms / Papers

Iq distance functions
https://iquilezles.untergrund.net/www/articles/distfunctions/distfunctions.htm

Jon Baker, The Distance Estimator Compendium (many distance distance functions with awesome Fractal primitives)
https://jbaker.graphics/writings/DEC.html

Max Norm ellipsoid (sphere with transforms)
https://www.shadertoy.com/view/Mt2XWG

Efficient Max-Norm Distance Computation and Reliable Voxelization PDF
http://gamma.cs.unc.edu/RECONS/maxnorm.pdf

Distance to Quadratic Bezier
https://twitter.com/jbaker_graphics/status/1415767199382396940
3D: https://www.shadertoy.com/view/7dfGD2

GPU-Driven Rendering Pipelines / Cluster rendering
https://advances.realtimerendering.com/s2015/aaltonenhaar_siggraph2015_combined_final_footer_220dpi.pdf

Making Signed Distance Field Textures With Jump Flooding Algorithm (2D)
https://blog.demofox.org/2016/02/29/fast-voronoi-diagrams-and-distance-dield-textures-on-the-gpu-with-the-jump-flooding-algorithm/
https://blog.demofox.org/2016/03/02/actually-making-signed-distance-field-textures-with-jfa/

Enhanced Sphere Tracing
https://erleuchtet.org/~cupe/permanent/enhanced_sphere_tracing.pdf

## Talks

Advanced-Procedural-Rendering-with-DirectX
https://www.gdcvault.com/play/1015726/Advanced-Procedural-Rendering-with-DirectX

Advanced Graphics Techniques Tutorial: GPU-Based Clay Simulation and Ray-Tracing Tech in 'Claybook'
https://www.gdcvault.com/play/1025030/Advanced-Graphics-Techniques-Tutorial-GPU
https://www.youtube.com/watch?v=Xpf7Ua3UqOA

Rendering mandelbox fractals faster with cone marching
https://www.youtube.com/watch?v=4Q5sgNCN2Jw&t=530s
http://www.fulcrum-demo.org/wp-content/uploads/2012/04/Cone_Marching_Mandelbox_by_Seven_Fulcrum_LongVersion.pdf
https://www.pouet.net/prod.php?which=59072

Conemarching in VR / Developing a Fractal experience at 90 FPS / Johannes Saam / Mariano Merchante / FRAMESTORE
https://ubm-twvideo01.s3.amazonaws.com/o1/vault/gdc2018/presentations/Saam_Johannes_Merchante_Mariano_Conemarching%20in%20VR.pdf
https://www.gdcvault.com/play/1025454/Cone-Marching-in-VR-Developing

## Twitter discussions

BVH with blending
https://twitter.com/TheKristofLovas/status/1415000116629495808

fBM style displacement Inigo quilez @iquilezles
https://twitter.com/iquilezles/status/1414738043118899200
https://iquilezles.org/www/articles/fbmsdf/fbmsdf.htm

## Code

hg_sdf A glsl library for building signed distance functions by Mercury
https://mercury.sexy/hg_sdf/


