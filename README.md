
# CS330 Final Project

## How do I approach designing software?
- What new design skills has your work on the project helped you to craft?

I have learned how to design simple rendering interfaces that include lighting, texturing, materials, and objects. All of this work comes together to create a solution capable of rendering a complex 3D scene.

- What design process did you follow for your project work?

My main design process involved implementing render methods to facilitate the rendering and global transformation of 3D objects composed of pre-assembled primitives.

- How could tactics from your design approach be applied in future work?

Learning what your project needs and how to efficiently solve problems is the best approach to designing code. In the early stages of the project, I realized that my scene would need multiple books. To address this, I created a renderBook() method, which can be called multiple times to render multiple books. The method provides global transformation parameters to position and scale each book as needed.
## How do I approach developing programs?

- What new development strategies did you use while working on your 3D scene?

One development strategy was to create helper functions in advance to simplify the creation of transformation matrices and control the order of transformations. For example, the default project used an XYZ rotation order, but I needed a ZYX rotation order to rotate the cylinder around the X-axis first rather than last. I understood this requirement because I had learned that changing the rotation order produces different results.


- How did iteration factor into your development?

While developing the solution, iteration was a crucial part of the process. I needed to compile the software multiple times to test various parameters, such as lighting configuration, materials, textures, and object positioning. Specifically, for object creation, I first built each object in a neutral position at the origin, composed of primitives. I then applied additional transformation matrices to place it within the global scene. This was a repetitive yet creative process aimed at maximizing the quality of the scene.

- How has your approach to developing code evolved throughout the milestones, which led you to the project’s completion?

In each milestone, I completed the required code additions, which helped me understand how to approach later milestones. For example, in one milestone where I needed to create a 3D object, I realized the burden of applying a single matrix transformation pass to each primitive and positioning them individually in the scene. This experience led me to create the renderObject methods, which simplified the complexity of composing the scene.

## How can computer science help me in reaching my goals?
- How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?

Computer graphics have many applications in academia, such as fluid simulations, and GPU computing can also be leveraged for machine learning research. In general, computer graphics techniques teach the effective use and synchronization of the CPU and GPU, which has numerous academic applications for code development in an educational context.

- How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?

Computer graphics techniques help students learn to code more efficiently and effectively. When studying computer graphics, one learns that the GPU is not only useful for rendering graphics but also for handling general, repetitive workloads. This knowledge is extremely valuable in a professional setting, as it allows you to differentiate your work from that of others.
