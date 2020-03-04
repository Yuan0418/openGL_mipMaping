# openGL_mipMaping
Reference: https://learnopengl.com/Getting-started/Textures
Libraries have been used: glad, glfw, stb_image, glm

Depending on the distance between objects and the viewer, OpenGL can use a different texture that
best suits the distance to the object. Each subsequent texture is twice as small compared to the previous
one. OpenGL is then able to load the correct texture, and there's less cache memory involved when
sampling that part of the texture.

demo: https://www.youtube.com/watch?v=6kZJJw5ughI
