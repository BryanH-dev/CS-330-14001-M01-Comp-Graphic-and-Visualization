# 3D Scene Visualization – Final Project

This project is a 3D graphics application built in C++ using OpenGL and GLSL, developed in Visual Studio. It recreates a real-world 2D image into an interactive 3D scene featuring low-polygon models, textures, lighting, and camera navigation.

##  Tech Stack

- **Language:** C++
- **Graphics Library:** OpenGL
- **Shader Language:** GLSL
- **Environment:** Visual Studio
- **Controls:** Keyboard + Mouse

###  3D Object Creation
- Created 4+ low-poly 3D objects using combinations of the following primitives:
  - Box
  - Cylinder
  - Sphere
  - Plane
- At least one object built using multiple combined shapes
- Polygon count for each object kept under 1,000 triangles

###  Texturing
- Applied high-resolution (≥1024x1024) royalty-free textures to at least two objects
- UV mapping used to project textures accurately

###  Lighting
- Implemented Phong shading (ambient, diffuse, specular)
- Included two light sources:
  - One white directional or spotlight
  - One colored point light
- Positioned to light all objects in the scene effectively

###  Camera & Navigation
- **WASD**: Move forward/backward, strafe left/right  
- **QE**: Move up/down  
- **Mouse**: Control pitch/yaw (orientation)  
- **Scroll wheel**: Adjust movement speed  

###  Projection Toggle
- Switch between **Perspective** and **Orthographic** views with a single key press

##  How to Run

1. Clone the repository
2. Open the `.sln` file in Visual Studio
3. Ensure all textures are located in the correct `resources/` or `textures/` folder
4. Build the solution (`Ctrl + Shift + B`)
5. Run the program (`F5`) to explore the scene

##  Design Decisions

- Selected 2D reference image for clear geometric structure and depth
- Modeled real-world objects using primitive shapes to simplify complexity
- Modularized code for rendering, input, camera, lighting, and texturing
- Carefully positioned objects to match the layout of the reference image

##  Reflection

This project demonstrates a strong foundation in 3D modeling, OpenGL programming, and real-time interactivity. Code is structured and well-documented, following best practices for maintainability and readability.

