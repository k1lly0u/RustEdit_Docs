# Terrain Tool

The terrain tool is a collection of various tools used to manipulate the terrain mesh. You can use these tools to create any kind of terrain you want.

**Brush Options**
*Size* is the size of the brush in height map pixels.
*Opacity* is the strength of the brush.
*Rotation* is the rotation of the brush

**Modification Tools**

The terrain tool has 15 modification tools in total;

*Raise/Lower* tool will raise or lower the terrain using the brush shape as a stencil. By default the brush will raise the terrain
or hold ALT to invert the brush to lower the terrain

![Raise Terrain](https://i.gyazo.com/d5aa5dee28130ca26d29e99010563300.png) ![Lower Terrain](https://i.gyazo.com/e53d4942d80b34aa8e3ac04265baac7e.png)

*Flatten* will flatten the terrain to the designated height set. You can set the brush height either via the Height slider, or by moving your mouse
the the position you want to sample and hold CTRL and right mouse click

![](https://i.gyazo.com/ec5b2de94f376ce7010cd237416d9aa4.png)

*Smooth* will smooth out terrain. You can adjust how much smoothing to apply by changing the Opacity value

![](https://i.gyazo.com/13ab5aa35af55fbe9017f518a53d602f.png)


*Bridge* connects 2 points in world space and creates an even grade between them. First you set the source position by holding SHIFT and clicking the 
mouse, then you can click anywhere else to create a even grade between those 2 points

![](https://i.gyazo.com/a6d6711e75fc92bae7ad8bea1ef40fc9.png)

*Clone* takes a sample from a source position and copies it elsewhere. First you set the source position by holding SHIFT and clicking the mouse, then
you can click anywhere else to copy to that location. As you drag the mouse the source position matches the movement so you can effectively paint the 
copy across the map
The clone tool has 3 movement behaviours;
Snap - Will snap the source position back to its original position when you release the mouse
Follow On Paint - The source position will stay where it last was when you releae the mouse
Fixed - The source position will always stay where you set it, even when you drag your mouse around

![](https://i.gyazo.com/b0720c30c53c905af5e1cdd8ad846934.jpg)


*Erode* erodes away terrain height away from the highest point in the brush

*Pinch* pinches the terrain in towards the center of the brush. You can also bulge out from the center by holding SHIFT when using

*Ridge Erode*
