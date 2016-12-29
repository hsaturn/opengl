cmake_minimum_required (VERSION 2.8.11)
project (tuto_1)

file(GLOB SOURCES *.cpp)
add_executable(tuto_1 ${SOURCES})
target_link_libraries(tuto_1 glfw GLEW GL)
