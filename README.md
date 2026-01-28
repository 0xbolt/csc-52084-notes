# csc-52084-notes
My notes for CSC-52084: Image Synthesis at École Polytechnique.

## Schedule
### 1. Introduction
- Rendering as image synthesis from 3D numerical models and simulation of light transport
- Physically-based vs stylized rendering; offline vs real-time constraints
- PBR as radiometric measurement at the sensor; role of GPU parallelism
- Rendering pipeline overview (“rendering wheel”)
- Applications (VFX, games, CAD) and brief historical context
- 3D scene structure: camera, geometry, materials, lights, animation
- Surface meshes as standard geometry; vertex attributes and interpolation
- Normals (per-face, per-vertex, interpolated)
- Digital image representation, RGB/sRGB, HDR vs LDR
- Image processing stages in rendering
- Basic C++ notions for graphics programming

#### References

#### Related Resources

### 2. Rendering Algorithms & Visibility
- Rendering algorithm decomposition: preprocessing, visibility, shading, post-processing
- Visibility problems and queries; forward (rasterization) vs backward (ray tracing) rendering
- Rasterization pipeline: projection, triangle discretization, fragment generation
- Depth ordering approaches: painter’s algorithm and Z-buffer
- Rasterization limitations (aliasing, transparency, global effects)
- Culling techniques: frustum, backface, occlusion
- Transparency handling and order-dependent vs approximate solutions
- Rasterizer application structure and GPU execution model
- Graphics pipeline stages and data layout (buffers, textures)
- Modern graphics APIs and programmable shader stages
### 3. Appearance
- Appearance as radiance-based color response at a surface point
- Light field formulation and radiometric quantities
- Virtual light sources and distance-based attenuation
- Analytical lighting vs environment lighting (HDR maps)
- Rendering equation and separation of emission, lighting, and reflectance
- Direct lighting approximation and motivation for Monte Carlo integration
- BRDF concept and physical constraints
- Diffuse and specular components of reflection
- Empirical models (Lambert, Phong, Blinn-Phong)
- Microfacet theory: roughness, normal distributions, Fresnel, geometry term
- Influence of roughness and Fresnel on perceived material appearance
- Color handling in materials (albedo, specular color)

## Books
- Real-Time Rendering
- Physically Based Rendering
- Computer Graphics: Principles and Practice
- Fundamentals of Computer Graphics

## Related Courses
- [CS248A](https://gfxcourses.stanford.edu/cs248a/winter25)
- [CMU 15-462](https://15462.courses.cs.cmu.edu/fall2021/)

## Miscellaneous
- [GPU Gems](https://developer.nvidia.com/gpugems/gpugems/contributors)
- [Scratchapixel](https://www.scratchapixel.com)
- [Shadertoy](https://www.shadertoy.com)
- [Graphics Codex](https://graphicscodex.com)
- [Real-Time Rendering Resources](https://www.realtimerendering.com)
- [WebGPU Fundamentals](https://webgpufundamentals.org/)
- [WebGPU Best Practices](https://toji.dev/webgpu-best-practices/)
- [LearnWebGPU](https://eliemichel.github.io/LearnWebGPU/)
- [LearnOpenGL](https://learnopengl.com)
- [Nori Renderer](https://wjakob.github.io/nori/)
- [Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html)
- [Real-Time Rendering Bibliography](https://www.realtimerendering.com/refs.html)
- [Physically Based Rendering Bibliography](https://www.pbr-book.org/4ed/References)
- [How to Vulkan in 2026](https://www.howtovulkan.com)
- [Catlike Coding (Unity)](https://catlikecoding.com)
- [Physically Based Rendering in Filament](https://google.github.io/filament/main/filament.html)

## Blogs
- [Inigo Quilez](https://iquilezles.org)
- [Brian Karis](https://graphicrants.blogspot.com)
- [Adrian Courrèges](https://www.adriancourreges.com/blog/)
- [Stephen Hill (Self Shadow)](https://blog.selfshadow.com)
- [Peter Shirley](https://psgraphics.blogspot.com)
- [Eric Haines](https://www.realtimerendering.com/blog/)
- [Jendrik Illner](https://www.jendrikillner.com/index.html#newsletter)
- [Matt Pharr](https://pharr.org/matt/blog/)
- [Sebastian Lagarde](https://seblagarde.wordpress.com)
