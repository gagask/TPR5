cmake_minimum_required(VERSION 3.15)
project(TPR5)

set(CMAKE_CXX_STANDARD 98)

add_executable(TPR5 Coco.cpp
        APC_Const.h
        APC_Math.h
        APC_Math.cpp
        APC_PrecNut.cpp
        APC_PrecNut.h
        APC_Spheric.cpp
        APC_Spheric.h
        APC_Sun.cpp
        APC_Sun.h
        APC_Time.cpp
        APC_Time.h
        APC_VecMat3D.cpp
        APC_VecMat3D.h
        )