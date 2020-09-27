cmake_minimum_required(VERSION 3.17)
project(myGraph)

set(CMAKE_CXX_STANDARD 11)

#add_executable(myGraph main.cpp adjacencyList.h DFS_LGraph.cpp adjacencyList.cpp adjacencyMatrix.h BFS_MGraph.cpp)
add_executable(myGraph main.cpp adjacencyMatrix.h BFS_MGraph.cpp)