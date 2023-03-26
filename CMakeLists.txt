cmake_minimum_required(VERSION 3.0.0)
project(dz1 VERSION 0.1.0)

# include(CTest)
# enable_testing()
add_subdirectory(lib/utils)


add_executable(dz1 src/main.cpp)
target_link_libraries(dz1 utils)
# set(CPACK_PROJECT_NAME ${PROJECT_NAME})
# set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
# include(CPack)
