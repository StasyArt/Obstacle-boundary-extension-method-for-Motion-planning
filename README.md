# Obstacle-boundary-extension-method-for-Motion-planning
Motion planning with exact decomposition: Obstacle boundary extension method

## Algorithm:
1. The boundaries of polygonal obstacles continue until they collide with other obstacles or configuration space boundaries.
2. The midpoints of the obtained segments are found. The found points are the vertices of the channel graph.
3. The vertices are connected by lines that do not intersect obstacles to obtain a connected channel graph.
4. Points describing the initial and final positions of the robot are attached to the resulting graph with edges.
5. The search for a path in the graph is implemented.

## Python Implementation:
1. The result of the obstacle generator.

![image](https://user-images.githubusercontent.com/46959062/211151734-308c71ec-9e08-4c5c-80b7-284ae9a91f0d.png)

2. Reading configuration space.

![image](https://user-images.githubusercontent.com/46959062/211151730-3895e126-090f-4773-87d5-ae2552e2e7a8.png)

3. Continuing Obstacle Boundaries to Intersect with Configuration Space Boundaries.

![image](https://user-images.githubusercontent.com/46959062/211151723-5a87a83c-9558-4bd1-ad2c-357a3fca7986.png)

4. Continuation of the boundaries of obstacles to the intersection with the boundaries of the conf. space and other obstacles.

![image](https://user-images.githubusercontent.com/46959062/211151713-ad0234ba-0593-441c-af45-a540a8bfc0fe.png)

5. Construction of the midpoints of the drawn segments.

![image](https://user-images.githubusercontent.com/46959062/211151716-51e05819-661d-40e9-9b38-c3f43789c65d.png)

6. Mapping the vertices of the channel graph.

![image](https://user-images.githubusercontent.com/46959062/211151708-9cf8e1a1-071e-4899-8b92-542d6e5afb09.png)

7. Building a channel graph

![image](https://user-images.githubusercontent.com/46959062/211151700-e197c3bd-5a4c-46d3-aeaa-afa901605987.png)

8. Finding a path in a graph

![image](https://user-images.githubusercontent.com/46959062/211151682-284a2866-3d8e-4a1f-bd47-098feba34a23.png)

9. The result of the program.

![image](https://user-images.githubusercontent.com/46959062/211151690-3c3f4c0b-ea90-4a8f-bf40-7276269b1402.png)

