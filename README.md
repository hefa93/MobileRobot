# Mobile Robot Application

## Overview

Welcome to the Mobile Robot Application project! This project involves the development of a mobile robot equipped with various sensors for mapping and navigation, motor control for movement, and a sophisticated software stack to manage these components. The project utilizes a Git workflow with specific pull request rules, includes unit testing with Google Test (gtest), and is integrated with a build server for continuous integration and deployment.

## Features

- **Sensors**: Integration with various sensors combined with state extimations algorithms for real-time environment perception.
- **Mapping**: Implementation of SLAM (Simultaneous Localization and Mapping) algorithms to create and update maps of the environment.
- **Motor Control**: Precise control of motors for accurate navigation and obstacle avoidance.
- **Modular Software Design**: Separation of concerns with distinct modules for sensors, mapping, and motor control.
- **Unit Testing**: Comprehensive unit tests using Google Test (gtest) to ensure reliability and robustness.
- **Continuous Integration**: Automated build and test processes using a build server to maintain code quality.

## Getting Started

### Prerequisites

- CMake 3.10 or higher
- GCC or Clang compiler
- Google Test (gtest)
- Git
- A Jenkins build server

### Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/hefa93/mobilerobot.git
