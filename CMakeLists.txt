cmake_minimum_required(VERSION 3.1)

project(simple_template_c)

# set(CMAKE_CXX_STANDARD 11)
# set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -O3")

# NOTE: The "" is needed to pass an empty list of sourcefiles
add_executable(simple_template_c "")

add_subdirectory(src)
#add_subdirectory(test)

# Add static lib
#target_link_libraries(simple_template_c ${CMAKE_CURRENT_SOURCE_DIR}/libs/exampleLib/libExample.lib)