# cg-ray-tracing
Implementation of Ray Tracing along with Recursive Ray Tracing upto two levels. The program uses OpenGL to render points onto the display. The program takes care of shadows, reflection, refraction, multiple light sources, light attenuation and works on the planes and circles given as input

#The format of input file is shown - 

<Size of a point( in terms of pixels)\>
<How triangles and spheres will be interpolated\>

<No. of spheres>
FOR EACH SPHERE
<Radius>
<Position>
<ka, kd, ks, n>
<refl_cof, refr_cof, refr_ind>

<No. of polygons>
FOR EACH POLYGON
<Vertex 1>
<Vertex 2>
<Vertex 3>
<ka, kd, ks, n>
<refl_cof, refr_cof, refr_ind>

<Eye position>
<Eye lookat>
<Eye up vector>

<Near plane distance>
<Far plane distance>
<Window width> <Window height>

<No. of light sources>
FOR EACH LIGHT SOURCE
<Position> <Intensity>

<Constant attenuation> <Linear attenuation> <Quadratic attenuation>

<Ambient light intensity>
