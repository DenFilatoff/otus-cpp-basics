# This is required in all CMakeLists Selecting a nice minimum version and range
cmake_minimum_required(VERSION 3.1...3.10)

# We can call the project anything we want Listing the language(s) avoids the C
# + CXX default
project(hw02 LANGUAGES C)

# We need an executable target
add_executable(hw_example simple.cpp)
