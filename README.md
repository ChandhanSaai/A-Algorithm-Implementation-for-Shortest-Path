


# A* Algorithm Implementation for Shortest Path ENPM661 PROJECT3
### 
    Author 1: Abraruddin Syed UID: 120109997
    Author 2: Vijay Chevireddi UID: 119491485
    Author 3: Chandhan Saai Katuri UID: 120387364



This repository contains an implementation of the A* (A-star) search algorithm, written by Vijay Abraruddin Chandhan. The A* algorithm is a popular choice for pathfinding and graph traversal, which is the process of finding a path between multiple points, called "nodes"

## Prerequisites

- Python 3.x
- OpenCV (cv2) library
- NumPy library
- math library

You can use "a_star_Chandhan_Vijay_Abrar.py"  which purely uses mathematical equations to create obstacles and walls and also to check whether the new node is in obstacle or not, instead of using openCV functionality.

## Usage V1

1. Clone the repository or download the `a_star_Chandhan_Vijay_Abrar.py` file.
2. Install the required libraries using pip:
   ```
   pip install opencv-python numpy
   ```
3. Run the script:
   ```
   python a_star_Chandhan_Vijay_Abrar.py
   ```
4. Follow the prompts to input the start and goal points.


### Example Input

After running the script, you will be prompted to input the start and goal points. Here's an example of how you might provide this input:

```

Click ENTER for entering default value 
Enter by how much the obstacles and map walls need to be bloated (default 5):
Enter Robot Radius (default 5):
Enter Step Size (1 to 10, default 5):
Please Wait, Obstacle Space is Building
Enter the start point (x, y, angle): 
Enter the end point (x, y, angle):

```
5. The script will display the obstacle map and explored nodes with the shortest path highlighted in blue.

## Results
![Video Demo](https://github.com/SYED-ABRARUDDIN/ENPM661_PROJECT3/blob/main/Shortest_Path_v1.gif)

This is more optimized vesion of above it takes approx 1/10th time of above execution

## Usage V2

1. Clone the repository or download the `a_star_vijay_abraruddin_chandhan.py` file.
2. Install the required libraries using pip:
   ```
   pip install opencv-python numpy
   ```
3. Run the script:
   ```
   python a_star_vijay_abraruddin_chandhan.py
   ```
4. Follow the prompts to input the start and goal points.


### Example Input

After running the script, you will be prompted to input the start and goal points. Here's an example of how you might provide this input:

```
Click ENTER for entering default value 
Enter by how much the obstacles and map walls need to be bloated (default 5):
Enter Robot Radius (default 5):
Enter Step Size (1 to 10, default 5):
Enter start point (x, y,theta):  (default: 50,50,0):
Enter goal point (x, y,theta):  (default: 1150,50,30):
Goal Threshold reached with correct orientation: (1147,745,30)

```

In this example, the start point is at coordinates (50, 50, 0) and the goal point is at coordinates (1150, 50, 30). Please note that the coordinates should be within the dimensions of your obstacle map.



5. The script will display the obstacle map and explored nodes with the shortest path highlighted in blue.


## Customization

- You can modify the obstacle map by changing the dimensions, adding or removing obstacles, or adjusting their properties (shape, color, thickness, transparency).
- The visualization of explored nodes can be customized by changing the `explored_interval` variable to control the frequency of updates.



## Acknowledgements

- The script is based on A* algorithm for pathfinding.
- The visualization is done using the OpenCV library.

## Results
![Video Demo](https://github.com/SYED-ABRARUDDIN/ENPM661_PROJECT3/blob/main/shortest_path_gif.gif)
