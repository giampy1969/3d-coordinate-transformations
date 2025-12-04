# 3d-coordinate-transformations
3D Space Coordinate Transformations for Robotics Applications

[![View 3D Rotations on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/956-3d-rotations)

This folder contains 3 files (m-functions) :

- t2x.m Transformation Matrix to Generalized Position Vector.
- x2t.m Generalized Position Vector to Transformation Matrix.
- m2m.m Mass/Inertia Tensor transformation with coordinate change.

In the Generalized Position Vector the orientation can be expressed with:
  -  unit quaternion, 
  -  Euler angles xyz (roll, pitch, and yaw),
  -  Euler angles zyz (rotation, precession, and mutation),
  -  unit vector and rotation angle,
  -  Denavitt-Hartemberg parameters.
Conversion between the above orientation systems can be easily achieved.

The three files work independently on each other, but since they work
on the same objects it is somewhat useful to keep them in the same folder. 

For more detailed information see the help texts of the three functions.

January 2001

For a quick reference to built-in methods in the Robotics System Toolbox&copy; see [Coordinate Transformations in Robotics](https://www.mathworks.com/help/robotics/ug/coordinate-transformations-in-robotics.html).

For more extensive inroduction to rotation matrices, see [Rotation Matrices](https://en.wikipedia.org/wiki/Rotation_matrix).
