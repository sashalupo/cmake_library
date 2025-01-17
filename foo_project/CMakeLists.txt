cmake_minimum_required(VERSION 3.10)
project(foo_project)

set(CMAKE_CXX_STANDARD 11)

find_package(foo_library REQUIRED)
message(STATUS "Found geo: ${geo_LIBRARIES}")
message(STATUS "Found dirs: ${foo_lib_DIR}")

add_executable(${PROJECT_NAME})

target_sources(${PROJECT_NAME}
    PRIVATE
    src/main.cpp
)

target_link_libraries(${PROJECT_NAME} PRIVATE foo::foo_library)
