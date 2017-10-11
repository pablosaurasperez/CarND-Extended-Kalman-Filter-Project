# Extended Kalman Filter Project 
By Pablo Sauras Perez

## Submission code location
The submited code can be found in the **src** directory. In particular, the following files have been modified:
- FusionEKF.cpp
- kalman_filter.cpp
- tools.cpp

## Important Depencencies
As stated in the project description, these are the important dependencies.
- cmake >= 3.5
- make >= 4.1 (Linux, Mac), 3.81 (Windows)
- gcc/g++ >= 5.4

## Basic Build Instructions
As stated in th project description, from the project top directory:
- ```mkdir build && cd build```
- ```cmake .. && make```
-   ```./ExtendedKF```

## Results
As it can be seen in the next figures, ```px, py, vx, vy``` output coordinates have an **RMSE <= [.11, .11, 0.52, 0.52]** when using the file: _obj_pose-laser-radar-synthetic-input.txt_ which is the same data file the simulator uses for Dataset 1.

![Alt text](/images/DS1_Result.jpg?raw=true "RMSE for Dataset 1")

![Alt text](/images/DS2_Result.jpg?raw=true "RMSE for Dataset 2")

As it can be seen, both meet specifications.
