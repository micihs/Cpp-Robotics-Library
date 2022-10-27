## Cpp-Robotics-Library
A series of robotics algorithms implemented in C++

## Requirements

- cmake
- opencv 3.3+
- Eigen 3
- [CppAD](https://www.coin-or.org/CppAD/Doc/install.htm) / [IPOPT](https://www.coin-or.org/Ipopt/documentation/node14.html) (*for MPC convex optimization*) [install tips](https://github.com/udacity/CarND-MPC-Quizzes/blob/master/install_Ipopt_CppAD.md)

## Build

  $ mkdir build
  $ cd build
  $ cmake ../
  $ make -j 8
  
 Find all the executable files in ***build/bin***
