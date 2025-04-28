# CS-330

Designing the scene
I start every graphics job by naming the draw calls I’ll need—here that was “render-scene,” “render-laptop,” “render-books,” “render-cup,” and “render-mouse.” Once those five stubs existed I could work inside each one without touching the others. That small, fixed API kept the project from sprawling and made late requests—like adding hinge cylinders or shifting the laptop—quick edits instead of rewrites.

Building the code
Early milestones were full of raw glUniform calls; changing a color meant hunting through dozens of lines. I replaced those repeats with tiny helpers (SetTransformations, SetShaderColor, SetShaderTexture). One helper change now updates the whole scene, so scaling everything 1.5× or moving the camera toggle to the O key took minutes. The habit of wrapping boilerplate is the biggest practice I’ll carry forward.

Value to my goals
Writing the math for model-view matrices and tweaking Phong lights made classroom linear-algebra feel concrete. Those skills translate straight to any real-time data-viz or game-engine work I take on next. Just as useful, the project drilled a workflow of “prototype fast, refactor immediately,” a pattern that matters in every software job—not just OpenGL.
