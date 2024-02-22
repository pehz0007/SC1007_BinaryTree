cmake_minimum_required(VERSION 3.27)
project(SC1007_BinaryTree C)

set(CMAKE_C_STANDARD 11)

enable_testing()

foreach (X RANGE 1 4)
    add_subdirectory(src/q${X})
endforeach ()
