# RRT (Rapidly-exploring Random Tree) Navigation Algorithm
## Purpose: 
RRT is an optimization algorithm for finding paths in high-dimensional space, which is very useful for robots to navigate through obstacles.
## How it works:
Starting from the initial position, the algorithm expands the search tree by generating random points in space.
Each new point is checked to ensure that it does not collide with obstacles. If possible, it connects to the current tree.
As the tree grows, the algorithm finds a path from the starting point to the destination, while also being able to adapt to changes in the environment.

# Yolo (You Only Look Once) Algorithm
## Purpose: 
Yolo is one of the fastest object recognition algorithms available today, allowing robots to recognize and classify multiple objects in real time.
## How it works:
Yolo divides the image into a grid and predicts the bounding box for each object in each grid cell.
Each bounding box comes with a probability of the presence of an object, which helps the robot recognize and classify what it sees.
Yolo is capable of processing hundreds of frames per second, making it ideal for applications that require fast response.

# Integration Between RRT and Yolo
## When combining RRT and Yolo on Jetson Nano, the robot can:
Recognize and determine the distance to objects: Yolo helps the robot detect surrounding objects, while RRT calculates the optimal path to avoid collisions.
Smart path planning: Based on information from Yolo, RRT can adjust its path to safely and efficiently overcome obstacles.
Adapt to dynamic environments: The robot can automatically adjust its behavior based on new objects appearing in the environment, thanks to Yolo's real-time recognition capabilities.

https://github.com/user-attachments/assets/82ad11ab-8727-4e50-9716-ae98289eeb89

https://github.com/user-attachments/assets/0acbe8e5-27cd-4544-8ecd-db77a4d0f766

https://github.com/user-attachments/assets/fd2ad832-704b-4afa-b705-331a26b53cc7


