# CURVETOPIA: A Journey into the World of Curves
Welcome to CURVETOPIA, a groundbreaking project created for the Adobe Hackathon. Our mission is to revolutionize the way we identify, regularize, and beautify curves in 2D Euclidean space. This project aims to transform line art images into a set of beautifully defqined curves using cubic Bezier curves.

## Objective
Our goal is to create an end-to-end process where we take a raster PNG image of line art and output a set of curves defined as a connected sequence of cubic Bezier curves.
The project is divided into three principal challenges:

### 1. Regularize Curves
### 2. Exploring Symmetry in Curves
### 3. Completing Incomplete Curves
Challenges

 ## 1. Regularize Curves
In this challenge, we aim to identify and regularize specific shapes within a given set of curves. The task can be broken down into the following primitives:

	1. Straight Lines: Detect and regularize straight line segments.
	2. Circles and Ellipses: Identify curves where all points are equidistant from a center (circle) or have two focal points (ellipse).
	3. Rectangles and Rounded Rectangles: Distinguish between rectangles and rectangles with curved edges.
	4. Regular Polygons: Identify polygons with equal sides and angles.
	5. Star Shapes: Detect star shapes characterized by a central point with multiple radial arms.

**Activity:** The target use cases for this activity are hand drawn shapes and doodles. It is important to consider that not all shapes can be regularised. Your algorithm should be able to distinguish between them. Test your algorithms with different images containing various shapes and verify the results. 
## 2. Exploring Symmetry in Curves
This challenge focuses on identifying symmetry in closed shapes. Our approach will start with reflection symmetries, where we check for lines of symmetry that divide the shape into mirrored halves. The key tasks include:

	1. Symmetry Detection: Identify the presence of reflection symmetries.
	2. Bezier Curve Fitting: Transform shapes into sets of points and identify symmetry to fit identical Bezier curves.
## 3. Completing Incomplete Curves
In this section, we tackle the problem of completing curves that have been "planarized," meaning overlapping portions have been removed, leaving gaps or partial holes. The task involves:

	Shape Occlusion Levels:
	1. Fully Contained: e.g., one circle completely inside another.
	2. Partially Contained: e.g., half a circle occluded by another circle.

 **Activity:** The task is to explore the notion of curve completion (not object). The completion algorithm may be guided by smoothness, regularity and symmetry
	3. Disconnected: e.g., a circle interrupted by a long rectangle, resulting in two disconnected portions of the circle.

 
Qualifying_for_Round 2!_Uday_Raj_Sharma.jpg
