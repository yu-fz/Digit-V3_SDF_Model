# SDF Model File for Digit V3 from Agility Robotics

<p align="center">
  <img src="./readme/digit_screenshot.png" alt="digit_visual_mesh" width="400"/>
</p>

#

This package hosts SDF model files for the digit-v3 robot, along with its associated visual meshes and collision models. 

The SDF models are created with Drake in mind, and includes Drake-namespaced SDF tags to represent actuator dynamics that may be unsupported with other parsers.

Collision meshes for the digit-v3 upper body is generated from running [convex decomposition](https://github.com/gizatt/convex_decomp_to_sdf) of the visual-3D meshes for more accurate collisions.

<p align="center">
    <img src="./readme/digit_collision.png" alt="digit_collision_mesh" width="300">
</p>

Model parameters in these model files are derived from the official digit-v3.mjcf mujoco model file from Agility Robotics. 

Permission to repackage and re-distribute software from Agility Robotics hereby granted under: 

```
Copyright (c) Agility Robotics

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to
deal in the Software without restriction, including without limitation the
rights to use, copy, modify, merge, publish, distribute, sublicense, and/or
sell copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.
```