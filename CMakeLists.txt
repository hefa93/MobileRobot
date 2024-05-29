cmake_minimum_required(VERSION 3.10)

# Set the project name and version
project(MyLargeProject VERSION 1.0)

# Specify the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(MyLargeProject
    src/main.cpp
)

# Include directories
target_include_directories(MobileRobot PRIVATE include)

# Add compile options
target_compile_options(MobileRobot PRIVATE -Wall -Wextra -Wpedantic)

# Add libraries if needed (example)
# find_package(SomeLibrary REQUIRED)
# target_link_libraries(MobileRobot PRIVATE SomeLibrary::SomeLibrary)

# Add configuration file to the project
configure_file(config/config.json config/config.json COPYONLY)

# Set the output directory
set_target_properties(MobileRobot PROPERTIES
    RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin
)

# Optionally add tests
# enable_testing()
# add_subdirectory(tests)