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

Potatro, RayMarching and DistanceFields : a story of SphereTracing
https://xoofx.com/blog/2009/10/12/potatro-and-raymarching-story-of/

Ray Marching for Dummies!
https://www.youtube.com/watch?v=PGtv-dBi2wE

Electric Square, Raymarching Workshop
https://github.com/electricsquare/raymarching-workshop

2D Distance fields with Unity and Unreal
https://joyrok.com/SDFs-Part-Two

SDF Decomposition
http://zone.dog/braindump/sdf_clustering/

The smallest WebGL SDF raymarcher (135 bytes), with detailed source code and useful links
https://xem.github.io/articles/webgl_quest_2.html

SDF Generator using Compute Shaders in Unity
https://mateigiurgiu.com/unity-sdf-generator-part-1/
https://mateigiurgiu.com/unity-sdf-generator-part-2/

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

### Distance Field Modeler for Unreal Engine

https://twitter.com/SDFmodelerUE4

### Antimony
CSG (CAD) tool
https://www.mattkeeter.com/projects/antimony/3/
https://github.com/mkeeter/antimony

### Clayxels

Clayxels is the volumetric toolkit for Unity
https://assetstore.unity.com/packages/tools/game-toolkits/clayxels-165312

### unbound.io
Collaborative SDF editing
https://www.unbound.io/
https://twitter.com/unbound_io
https://on-demand.gputechconf.com/gtc/2017/presentation/s7777-florian-hoenig-a-road-to-3d-for-everyone.pdf

### Claybook
"Claybook is a unique world made entirely of clay. Shape your character and the world around you to overcome challenging obstacles."
https://store.steampowered.com/app/661920/Claybook/

### Signed
Signed is a Lua based 3D modeling and construction language and will be a unique way to create 3D content, objects as well as whole scenes, in high detail.
https://github.com/markusmoenig/Signed

## Demos

Bounding Volume Hierarchy (BVH) implementation for SDFs to reduce per ray distance measurements
https://youtu.be/2T2FqvtXqLw

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

Collection of smooth minimums, maximums, ramps, and absolutes.
https://www.shadertoy.com/view/ltf3W2

Segment Tracing Using Local Lipschitz Bounds (improve the marching step computation and accelerate the overall process.)
https://diglib.eg.org/handle/10.1111/cgf13951

Improved Alpha-Tested Magnification for Vector Textures and Special Effects (Valve 2007)
https://steamcdn-a.akamaihd.net/apps/valve/2007/SIGGRAPH2007_AlphaTestedMagnification.pdf

Massively Parallel Rendering of Complex Closed-Form Implicit Surfaces
https://www.mattkeeter.com/research/mpr/

Tom Duff, Interval Arithmetic and Recursive Subdivision for Implicit Functions and Constructive Solid Geometry
http://fab.cba.mit.edu/classes/S62.12/docs/Duff_interval_CSG.pdf

Raph Levien’s research on 2D blurred shapes
https://raphlinus.github.io/graphics/2020/04/21/blurred-rounded-rects.html

Interval Raymarching
https://dercuano.github.io/notes/interval-raymarching.html

GigaVoxels:A Voxel-Based Rendering Pipeline For Efficient Exploration Of Large And Detailed Scenes
http://maverick.inria.fr/Membres/Cyril.Crassin/thesis/CCrassinThesis_EN_Web.pdf

Adaptively Sampled Distance Fields: A General Representation of Shape for Computer Graphics
_ *Frisken, Perry, Rockwood, and Jones - 2000*
https://www.merl.com/publications/docs/TR2000-15.pdf

Kizamu: A System for Sculpting Digital Characters - *Frisken and Perry - 2001*
https://dl.acm.org/doi/abs/10.1145/383259.383264

Hierarchical hp-Adaptive Signed Distance Fields - *Koschier, Deul, and Bender - 2016*
http://interactive-graphics.de/index.php/research/98-hierarchical-hp-adaptive-signed-distance-fields

GPU-Accelerated Adaptively Sampled Distance Fields - *Bastos and Celes - 2008*
https://www.researchgate.net/profile/Waldemar-Celes/publication/4344580_GPU-accelerated_Adaptively_Sampled_Distance_Fields/links/00b7d522f51ab59cc9000000/GPU-accelerated-Adaptively-Sampled-Distance-Fields.pdf

Signed Distance Computation using the Angle Weighted Pseudo-normal - *Bærentzen and Aanæs - 2005*
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.107.9173&rep=rep1&type=pdf

Fast Winding Numbers for Soups and Clouds - *Barill, Dickson, Schmidt, Levin, and Jacobson - 2018*
https://www.dgp.toronto.edu/projects/fast-winding-numbers/

Non-linear Sphere Tracing for Rendering Deformed Signed Distance Fields - *Seyb, Jacobson, Nowrouzezahrai, and Jarosz - 2019*
https://cs.dartmouth.edu/~wjarosz/publications/seyb19nonlinear.html

Concurrent Binary Trees (with application to longest edge bisection)
https://onrendering.com/data/papers/cbt/ConcurrentBinaryTrees.pdf

Bounding Interval Hierarchies (BIH) - 2006
(for improved per Ray distance calculations)
https://people.cs.clemson.edu/~dhouse/courses/405/papers/bounding-interval-WK06.pdf

GPU accelerated BIH Construction - 2014
https://www.uni-weimar.de/fileadmin/user/fak/medien/professuren/Virtual_Reality/documents/publications/2014.bih_construction_using_dynamic_parallelism.pdf

## Talks

Dynamic Bounding Volume Hierarchies
(BVH methods applicable to BIH)
https://box2d.org/files/ErinCatto_DynamicBVH_GDC2019.pdf

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

Fluid and Particle Physics in PixelJunk Shooter. 2D fluids collision detection with SDF
https://www.gdcvault.com/play/1012447/Go-With-the-Flow-Fluid

Realtime sparse Distance Fields for game
https://gpuopen.com/gdc-presentations/2023/GDC-2023-Sparse-Distance-Fields-For-Games.pdf

## Twitter/Reddit discussions

BVH with blending
https://twitter.com/TheKristofLovas/status/1415000116629495808

fBM style displacement Inigo quilez @iquilezles
https://twitter.com/iquilezles/status/1414738043118899200
https://iquilezles.org/www/articles/fbmsdf/fbmsdf.htm

How is SDF stored in a octree?
https://www.reddit.com/r/VoxelGameDev/comments/ontjdf/how_is_sdf_stored_in_a_octree/h5vrbea/

Using @SebAaltonen's eikonal solver (https://shadertoy.com/view/ltGGRw) to fix interior/exterior of SDF after add/cut.
https://twitter.com/Calneon/status/1422316033071882243

Casey Muratori's helpful notes for Implicit Surfaces and Interval Arithmetic
https://hastebin.com/raw/orenawiwum

"my best idea right now is to start in the middle of the ray/bounds intersection, and add new samples at the half way point of every unknown segment of the ray until you find a hit with no unknown space preceding it"
https://twitter.com/ladyaeva/status/1201770482766364672

"the idea here is that you start at the graph leaves and work your way down to the graph root.  leaves emit geometry for basic shapes.  operators modify the mesh data, and so on."
https://twitter.com/ladyaeva/status/1410120245621239808

## Code

hg_sdf A glsl library for building signed distance functions by Mercury
https://mercury.sexy/hg_sdf/

Rust & Vulkan test projects. "The first test project renders 1 million cubes, each containing a 950 MB (uncompressed) distance field volume.
The second test project is going to be using sparse octree storing a hierarchy of distance field volume bricks."
https://github.com/sebbbi/rust_test

libfive is a software library and set of tools for solid modeling, especially suited for parametric and procedural design.
https://libfive.com/

## Conversion to Polygonal Mesh

isosurface: A project testing and comparing various algorithms for creating isosurfaces
https://github.com/Lin20/isosurface

Manifold Dual Contouring - *Schaefer, Ju, and Warren - 2007*
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.75.9707&rep=rep1&type=pdf

Dual Contouring Tutorial
https://www.boristhebrave.com/2018/04/15/dual-contouring-tutorial/
