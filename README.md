MASAT intial guess for SLAM
============================================
This repository contains the code for the MASAT algorithm. 

### Guide
Compile:
```sh
./make
```
Run:
```sh
./MASAT 'path_input_file' 'path_to_output_file'
```
The input files must be in .g2o format. There are some examples in the 'input_data' folder.

Once the inital guess is finished, we suggest using the [g2o](https://github.com/RainerKuemmerle/g2o) framework for optimization and visualization.

数据：http://mplab.sztaki.hu/masat_slam/masat_slam_data.zip

### Requirements
- Eigen (http://eigen.tuxfamily.org)

