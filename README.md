# Python Libraries Useful for Robotics Applications

## Transformation Library

An open source library for transformation functions useful for robotic applications (forward/inverse kinematics, path planning, etc.) The library provides access to various classes for working with three-dimensional vectors (Vector3_Cls), euler angles (Euler_Angle_Cls), quaternions (Quaternion_Cls), and homogeneous transformation matrices (Homogeneous_Transformation_Matrix_Cls). 

The library can be used within the Robot Operating System (ROS), Blender, PyBullet, Nvidia Isaac, or any program that allows Python as a programming language.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Transformation/                                             |

## Parametric Curves

An open-source library of parametric curves interpolation (Bézier, B-Spline) useful for robotics applications, such as path planning, etc. The library provides access to specific classes for working with two types of parametric curves: Bézier curves and B-Spline curves. The specific classes focus on the problem of interpolating both two-dimensional and three-dimensional curves from input control points.

The classes also include the methods to calculate the derivative of the individual curves, arc-length, bounding box, simplification of the curves, and much more. The B-Spline interpolation class contains a function to optimize control points using the least squares method.

The library can be used within the Robot Operating System (ROS), Blender, PyBullet, Nvidia Isaac, or any program that allows Python as a programming language.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Parametric_Curves                                           |

## Collision Detection

An open-source library for collision detection of bounding boxes (AABB, OBB), useful for robotic applications such as path planning, inverse kinematics, and so on. The library provides access to specific classes for working with both types of bounding boxes: Axis-aligned Bounding Boxes (AABB) and Oriented Bounding Boxes (OBB). The specific classes focus on solving problems related to shape intersections, point tests, and last but not least, line intersections. Each of these problems is solved primarily in 3D space.

The library can be used within the Robot Operating System (ROS), Blender, PyBullet, Nvidia Isaac, or any program that allows Python as a programming language.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Collision_Detection                                         |

## Trajectory Generation

An open-source library for generating trajectories using two different methods (trapezoidal, polynomial). The library provides access to various classes for working with multi-axis (Trapezoidal_Profile_Cls, Polynomial_Profile_Cls) trajectories as well as multi-segment (Multi_Segment_Cls) trajectories.

The trajectory profile, which contains position, velocity, and acceleration, is generated from input constraints explained in the individual classes.

The library can be used within the Robot Operating System (ROS), Blender, PyBullet, Nvidia Isaac, or any program that allows Python as a programming language.

|        Result         | Link                                                                                  |
| --------------------- | ------------------------------------------------------------------------------------- |
| GitHub                | https://github.com/rparak/Trajectory_Generation                                       |

## Contact Info:
Roman.Parak@outlook.com

## License
[MIT](https://choosealicense.com/licenses/mit/)
