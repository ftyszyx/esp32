# For more information about build system see
# https://docs.espressif.com/projects/esp-idf/en/latest/api-guides/build-system.html
# The following five lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.16)

set(PROJECT_VER "1.2.2")

# Add this line to disable the specific warning
add_compile_options(-Wno-missing-field-initializers)
message(STATUS "IDF_PATH: ${IDF_PATH}")
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(xiaozhi)

