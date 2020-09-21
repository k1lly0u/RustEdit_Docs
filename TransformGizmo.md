# Transform Gizmo

![](https://i.gyazo.com/62c0f7a43ca9f7e9e806fc7531b22190.png)

The transform gizmo and respective tool panel are enabled when you have a prefab or path point selected. 
You can use the transform gizmo to manipulate position, rotation and scale of objects.

You can either manipulate the position, rotation and scale values directly through the input fields in the tool panel, 
or you can use the gizmo tool.

The gizmo tool has 3 different modes, 1 for each transform type.

The move gizmo has the 3 axis lines, 3 squares, and a white box in the middle. The axis lines only move on that axis, 
the squares move on the 2 axes they are aligned with, and the white square moves on all axes at once.
![](https://i.gyazo.com/828d0ba34f845d3047d06cc5542db9a9.png)

The rotation gizmo has 3 circles, 1 for each axis. You can also click between the circles and rotate on all axes at once.
![](https://i.gyazo.com/248b36e3ebb0d5237e0b841b008dd856.png)

The scale gizmo has 3 axis lines, and a white box in the middle. The 3 lines manipulate each axis respectively and the
white box scales all 3 axes at once.

![](https://i.gyazo.com/35f0d9f3e082abad94fee2b03b662d99.png)


**Controls**
CTRL + W - Select the position tool
CTRL + E - Select the rotate tool
CTRL + R - Select the scale tool
CTRL + D - Duplicate selected object
CTRL + X - Switch the gizmo between local and world space
Left Mouse - Select object
CTRL + Left Mouse - Add object to current selection
ALT + Left Mouse - Remove a object from your current selection
Right Mouse - Deselect selected object
Delete - Delete selected object

Ctrl + Shift + Mouse0 - Moves your current selection to your mouse position
Ctrl + Shift + Mouse1 - Copy transform values from prefab that is clicked on to the current selection
CTRL + L - Locks your current selection, and prevents it from being clicked on
CTRL + ALT + L - Unlocks all locked prefabs
CTRL + H - Hides your current selection, making it invisible
CTRL + ALT + H - Unhides all hidden prefabs

**HINTS** 
Holding ALT while using the transform tool will move/rotate/scale the object at a much slower speed for precision control
Holding SHIFT while using the move tool or rotation tool snaps the values to the clostest whole number

**Difference between Local and Global space**
Global space is using the same direction of the world. Left will always be left, up will always be up
Local space is using the direction of the selected object. Left will be the objects left, and up will be the objects up direction. 
If you have a upside down object for example, local up would actually be down in global space

**Drag Selection** 
Hold down the left mouse button and drag the mouse to create a selection box. Any objects inside this box when you release the mouse will be selected.
Holding CTRL while using the selection box will add any unselected objects inside the box to your current selection
Holding ALT while using the selection box will deselect any selected objects inside the selection box from your current selection

**Grouping** 
You can assign prefabs a group number which makes selecting them easier. Grouping only lasts for the time your are editing and are cleared when changing map or exiting the editor
Press any number 1-0 to select the prefabs in the respective group
Press any number 1-0 while holding CTRL will assign your currently selected objects to that group number
Press any number 1-0 while holding SHIFT will add all objects from that group to your current selection
Double tap any number 1-0 to select that group and focus your camera on your selection
