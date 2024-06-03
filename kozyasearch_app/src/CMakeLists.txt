cmake_minimum_required(VERSION 3.28.0)
project(KOZYASEARCH)
add_executable(KOZYA main.cpp)



find_package(wxWidgets REQUIRED)
include(${wxWidgets_USE_FILE})
target_link_libraries(KOZYA PRIVATE ${wxWidgets_LIBRARIES})