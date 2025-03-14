Tensor Visualization Tool - README
Overview
This web application provides an interactive 3D visualization tool for exploring tensor transformations. It enables users to visualize how different tensor parameters affect the deformation of a unit sphere by displaying vector fields and their corresponding matrix representations.

Features
Interactive 3D Visualization: Real-time rendering of tensor transformations on a unit sphere using arrow vectors

Parameter Control: Adjust tensor components through intuitive sliders

Direct Matrix Editing: Edit the 3×3 tensor matrix directly and see immediate visual results

Multiple Viewing Angles: Examine the tensor from different perspectives (X-axis, Y-axis, Z-axis, or custom view)

Visual Aids: Toggle coordinate axes visibility

Reset Functionality: Quickly reset all parameters to zero

Mathematical Representation: View the corresponding mathematical equation and matrix representation

Mathematical Background
The application visualizes a second-rank tensor with the following components:

Isotropic component (a): Uniform scaling

Quadrupolar components (q terms): Represent deformations like stretching and compression

Antisymmetric components (t terms): Represent rotational effects

The tensor is represented by a 3×3 matrix:

text
⎡ a + ½q_{x²-y²} - ½q_{z²}   t_z + q_{xy}            t_y + q_{xz}        ⎤
⎢ -t_z + q_{xy}              a - ½q_{x²-y²} - ½q_{z²} -t_x + q_{yz}       ⎥
⎣ -t_y + q_{xz}              t_x + q_{yz}            a + q_{z²}           ⎦
How to Use
Adjust Parameters: Use the sliders to modify individual tensor components

View Transformation: Observe how the vector field on the sphere changes

Change Perspective: Click the view buttons to observe from different axes

Direct Editing: Enter specific values in the matrix input fields and click "Apply Matrix"

Reset: Click the "Reset All Sliders to 0" button to return to an untransformed state

Technical Implementation
Built using HTML, CSS, and JavaScript

3D visualization powered by Plotly.js

Mathematical notation rendered with MathJax


Browser Compatibility
This application works best in modern browsers that support WebGL for 3D rendering. It is recommended to use Firefox, Safari, or Edge for optimal performance.

Getting Started
Simply open the HTML file in a compatible web browser. No additional installation or setup is required.
