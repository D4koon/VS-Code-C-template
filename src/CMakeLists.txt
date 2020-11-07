# NOTE: If cmake_minimum_required() > 3.13 in the root CMakeLists is used then '${CMAKE_CURRENT_SOURCE_DIR}/' can be removed
target_sources(simple_template_c PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/main.cpp)
