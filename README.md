`X3D`  
&emsp; --------------- `Scene`  
&emsp; --------------- `Shape`  
&emsp;&emsp;&emsp;&emsp; --------------- `appearance`  
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; --------------- `material`  
&emsp;&emsp;&emsp;&emsp; --------------- `Cone`  
&emsp; --------------- `Box`


#### What is X3D ?
Extensible 3D (X3D) Graphics
X3D Graphics is the international standard for real-time 3D communication.

`X3D` 是一種專為網際網路而設計的三維圖像標記語言，現階段多數的 `Direct3D` 和 `OpenGL` **GLSL** 的特效都可以實現。

X(Extensible)3D: a complete solution for 3D on the web。





#### Support for explicit GLSL / ComposedShader added
The `X3D` Profile supports now explicit `GLSL shaders` utilizing the `X3D Shaders component`.  
`H3D` ::  
-- H3D::ShaderProgram class reference  
-- H3D::ComposedShader class reference  
-- X3D specification: Programmable shaders component

Vertex Shader:






**Shaders and X3D**:
GPU is given a set of 3D points (vertexes) connected into triangles. 
(1) For each vertex, some work should be performed,  
    at least to transform it from an object space into the clip space.  
(2) This is where we move and rotate our objects, and apply perspective projection. 
(3) Vertex shaders allow to replace this per-vertex work with a custom program written in a special shading    
    language. 
(4) When the vertexes are processed, the GPU performs rasterization, determining
    which screen pixels are actually covered by the triangles.     
(5) Then each pixel is drawn, which involves calculating the actual pixel color.





