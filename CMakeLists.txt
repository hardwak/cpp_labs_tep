cmake_minimum_required(VERSION 3.26)
project(tepLaby)

set(CMAKE_CXX_STANDARD 17)

add_executable(tepLaby main.cpp
        main.h
        memoryAllocation/modification.cpp
        memoryAllocation/modification.h
        memoryAllocation/CTable.cpp
        memoryAllocation/CTable.h
        memoryAllocation/memoryAllocationTasks.cpp
        memoryAllocation/memoryAllocationTasks.h
        operatorOverloading/CNumber.cpp
        operatorOverloading/CNumber.h
        mathTree/MathTree.cpp
        mathTree/MathTree.h
        Pointer/Pointer.cpp
        Pointer/Pointer.hpp
        Pointer/MySmartPointer.cpp
        Pointer/MySmartPointer.h
        Pointer/CRefCounter.cpp
        Pointer/CRefCounter.h
        Pointer/MyArray.cpp
        Pointer/MyArray.h
)
