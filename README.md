# CS 330: Computer Graphics and Visualization - Final Portfolio

**Student:** Noelle Agha  
**Instructor:** Ronald Bishop  
**Course:** CS 330 - Computer Graphics and Visualization  

---

## Project Overview
This repository showcases a low-polygon 3D kitchen scene constructed in C++ using Modern OpenGL, GLFW, GLEW, GLM, and `stb_image`. The scene models a realistic kitchen countertop workspace featuring a wooden bread box (composed of a scaled box mesh and spherical handle knob), a granite countertop plane, a backsplash wall, a cylindrical kitchen canister, and a conical potted plant. Light sources implement a multi-light Phong shading model (ambient, diffuse, specular) and interactive WASD and mouse camera navigation.

---

## Journal Reflection

### 1. How do I approach designing software?
* **What new design skills has your work on the project helped you to craft?**  
  Developing this 3D scene strengthened my ability to break down complex, real-world physical objects into combinations of basic 3D geometric primitives (boxes, spheres, cylinders, cones, and planes). Additionally, I crafted design skills in texture projection mapping, UV coordinate scaling, and multi-source Phong lighting design.
  
* **What design process did you follow for your project work?**  
  I followed an iterative, modular design process. I began with initial reference photograph selection and spatial planning, followed by constructing low-polygon meshes, applying custom texture mapping via `stb_image`, integrating shader uniform pipelines, and adding camera movement controls.

* **How could tactics from your design approach be applied in future work?**  
  The practice of decomposing complex systems into smaller, modular components applies directly to software engineering outside graphics. Designing modular classes (such as `SceneManager` and `ViewManager`) ensures that code stays organized, readable, and reusable across future C++ development projects.

---

### 2. How do I approach developing programs?
* **What new development strategies did you use while working on your 3D scene?**  
  Key development strategies included managing dynamic OpenGL texture unit bindings within shader uniform logic, handling transformation matrix pipelines using GLM, and debugging graphics rendering pipelines through step-by-step console logging.

* **How did iteration factor into your development?**  
  Iteration was critical throughout the term. For instance, when resolving texture mapping issues where secondary objects defaulted to identical textures, iteration allowed me to refine `SetShaderTexture` to rebind texture slot 0 on the fly before drawing each mesh.

* **How has your approach to developing code evolved throughout the milestones?**  
  My approach evolved from simply rendering isolated static primitive shapes to architecting a cohesive, fully lit, textured, and interactive 3D virtual environment using clean object-oriented design patterns.

---

### 3. How can computer science help me in reaching my goals?
* **How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?**  
  Understanding matrix transformations, vector mathematics, hardware acceleration, and memory buffer management deepens my foundational knowledge of systems architecture and low-level C++ programming needed for advanced computer science coursework.

* **How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?**  
  Graphics programming equips me with strong algorithmic problem-solving techniques, spatial visualization skills, and software design capabilities that translate directly to careers in software engineering, simulation development, and technical project management.
