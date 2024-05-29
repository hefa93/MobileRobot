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


### Git Workflow
   We follow a standardized Git workflow to maintain code quality and facilitate collaboration:

  1. **Branching:**

   main: Production-ready code.
   develop: Latest development changes.
   Feature branches: Created from develop for new features or bug fixes.

  2. **Pull Requests:**:

   All changes must be made through pull requests.
   Ensure the branch is up to date with develop before creating a pull request.
   Include a clear description of the changes.
   Pass all unit tests and linting checks.
   At least one reviewer must approve the pull request before merging.
   
   3. **Commits:**

   Write clear and concise commit messages.
   Follow the convention: type(scope): description (e.g., feat(mapping): add new SLAM algorithm).


### Contributing
We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Create a pull request against the develop branch.
Please adhere to our pull request rules and coding standards.

### License
This project is licensed under the GPL-3.0 license. See the LICENSE file for details.

### Contact
For questions, suggestions, or feedback, please open an issue on GitHub or contact fabian.heuer@freenet.de.

Happy coding!
