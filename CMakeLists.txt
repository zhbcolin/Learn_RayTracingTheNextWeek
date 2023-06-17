cmake_minimum_required(VERSION 3.25)
project(RayTracingtheNextWeek)

set(CMAKE_CXX_STANDARD 17)
include_directories(../src)

add_executable(test_render test/test_render.cpp)
add_executable(test_texture test/test_texture.cpp)
add_executable(test_spheres test/test_spheres.cpp)
add_executable(test_earth test/test_earth.cpp)
add_executable(test_emit test/test_emit.cpp)
add_executable(test_empty test/test_empty.cpp)
add_executable(test_cornell_box test/test_cornell_box.cpp)
add_executable(final_scene final_scene.cpp)

SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)