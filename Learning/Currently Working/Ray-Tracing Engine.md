#Rayoptics #Math #Programming
- The total idea here is to see how light bounce of the objects in real world and simulate it in code.
- To create the engine you need something
	- Our real world is 3D so we need a math class to act as a 3D world. Calling it a vec3(x,y,z).
	- It is a vector by mathematical definition so it should be able to perform basic vector operation line cross, dot product, creating a normalized vector and basic arithmetic operation with scaler.
	- We also need a RAY class and a writer function(To write image).
- This is the minimum set-up you need. After that comes the first hurdle the "Viewport".
- So a viewport is what the image see (i.e. It is a 2D - Window in 2d world where each box represent a pixel in original image. The aspect ratio(width/height) of viewport is same as desired image.)
- 