cmake_minimum_required(VERSION 3.17)
project(IM)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")

    add_executable(IM main.cpp utilityfunction.h BFM-SWM.h Deng-Distorted.h Deng-ROI.h Deng-CostScaled.h )
#endif()
