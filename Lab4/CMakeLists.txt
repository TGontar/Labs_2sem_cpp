cmake_minimum_required(VERSION 3.23)
project(Lab4)

set(CMAKE_CXX_STANDARD 20)

add_executable(Lab4 main.cpp geomclasses.h parallelogram/parallelogram.cpp parallelogram/parallelogram.h ellipse/ellipse.cpp ellipse/ellipse.h figuresset.h figuresset.cpp)
