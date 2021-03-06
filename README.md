Plancher
========

Floor board generator add-on for Blender

Create 'Tiles', 'Squares', 'Herringbone', 'Chevron', 'Ladder' or 'Fougere' pattern. 
Distribute the texture randomly or by phase en Edit Mode.

Object Mode
===========

SURFACE:
--------
Switch : draw the boards only if it concord will the length of the floor.

Count : Number of boards on the X axis

Length : Length of the floor on the Y axis

Height : Height of the floor

Random : Add randomness to the height of the floor

BOARD :
-------
Length : Length of the boards

Width : Width of the boards

Random : Add randomness to the width of the boards (not the length) 

GAP :
-----
Gap X : Add a gap between the boards on the X axis

Gap Y : Add a gap between the boards on the Y axis

If not "Unlock" :
- Shift : Shift the columns upside down using the "Nbr Shift" parameter
- Random : Add randomness to the shift
- Nbr Shift : Number of columns to shift // Length of the transversal (shift possible)

INTERVAL:
------------
Interval : Add a transversal board if there is a gap on the Y axis. By default, the length of the transversal is 'locked' on the "Nbr Shift" parameter. Use the "Unlock" check box to enter a specific value.

Unlock : Allow to change the length of the transversal with a specific value (only if there is a transversal)

Length (if "Unlock") : Enter a specific length to the transversal (no shift possible)

Column: Number of column used for the transversal

Row : Number of tranversals in the gap on the Y axis (only one if borders)

Gap : Gap between the transversals and borders on the Y axis

Random : Add randomness to the gap of the transversal

Glue : Glue the boards included in the interval on the X axis (based on "Nbr Shift" parameter)

If "Glue":
- Borders : Add borders defined by the length of the transversal (No shift, no unlock, no multiple rows, no tilt)

CHEVRON : (No shift)
-------
Tilt : Degrees of rotation of the boards. The length and the width of the board are preserved

Herringbone : Specific pattern of parquet where the boards are put together to form an 90 degrees angle

SEED :
-----
Seed : New distribution of randomness

Edit Mode
===========

Vertex / UV :
------------
Random Color : Number of color / vertex group to distribute randomly 

- All random : Each board will have a random color and the vertex group will be randomly distribute

Phase Color : Number of color / Vertex Group to distribute by "phase" or by boards

Seed : New distribution of randomness
