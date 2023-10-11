# OpenGL
Basic OpenGL constructs and functions to construct a cube out of vertex buffer objects, and different vertex and fragment shaders applied different coloration effects to the surfaces of 3D models.

SURFACE SHADER PROGRAMS:
  CUBE VERTEX BUFFERS:
    In the Mesh class, which can be found in scene/mesh.h, createCube() fills std::vectors with vertex data for the following attributes of a cube that spans the range [-1, 1] in the X,   Y, and Z axes (in world space):
    Position (glm::vec4)
    Normal (glm::vec4)
    UV (glm::vec2)

SURFACE SHADER UNIFORM HANDLE:
  Integer member variable in SurfaceShader() class acts as a handle to a uniform vec3 in the surface shader that represents the camera's position in world space.

SURFACE SHADER RESULTS:
  
  ![Lambert](https://github.com/JillRay973/OpenGL/assets/143532365/344ff096-a0c5-49d0-846d-5b3d06f4eaed)
  
  Lambert Shader
  
  ![BlinnPhong](https://github.com/JillRay973/OpenGL/assets/143532365/1b3059f0-0676-4f52-95ab-9e11bfc7a56c)
  
  Blinn-Phong Shader

  ![Matcap](https://github.com/JillRay973/OpenGL/assets/143532365/67231c4d-8444-4a51-8b21-b1f4ad818b43)
  
  Matcap Red Clay Shader

  ![chrome](https://github.com/JillRay973/OpenGL/assets/143532365/27b30906-0988-458f-93c6-767c9cf97645)
 
  Matcap Chrome Shader

  ![HeatMap](https://github.com/JillRay973/OpenGL/assets/143532365/c3160c2b-7471-451e-9a9d-eda53792dd23)
  
  Iridescent Heat Map Shader


POST PROCESS SHADER RESULTS:

  ![GaussianBlurPostProcess](https://github.com/JillRay973/OpenGL/assets/143532365/a92ba91b-2421-4ea1-a0cd-cef5c9d2ce24)
 
  Gaussian Blur Post Process Shader

  ![GreyscalePostProcess](https://github.com/JillRay973/OpenGL/assets/143532365/ee198cb6-ebe3-43ba-a52a-e4170c3934fa)
  
  Greyscale Post Process Shader

  ![BloomPostProcess](https://github.com/JillRay973/OpenGL/assets/143532365/330a055d-5c65-4a65-b495-6b66b88481ae)
  
  Bloom Post Process Shader

  ![SobelPostProcess](https://github.com/JillRay973/OpenGL/assets/143532365/a841c5f9-a4f0-493a-b156-309495dd32fb)
  
  Sobel Post Process Shader

  ![PixellatedWorleyNoisePostProcess](https://github.com/JillRay973/OpenGL/assets/143532365/c345029f-24fd-45a5-954d-9b2edfe71082)
  
  Worley Noise Pixellated Process Shader

  
