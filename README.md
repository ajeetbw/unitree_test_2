# Unitree Robot SDK Version 2
Unitree robot sdk version 2 is a comprehensive software development kit designed to provide a robust and efficient way to interact with Unitree robots. This SDK is built on top of a range of cutting-edge technologies, including C++, Eigen, and Boost, to provide a high-performance and flexible platform for robot control and development.

## Project Description
The Unitree Robot SDK Version 2 is designed to provide a unified interface for controlling and interacting with Unitree robots. The SDK provides a range of features, including motion control, sensor integration, and communication protocols, to enable developers to build a wide range of applications, from simple robotic tasks to complex autonomous systems. The SDK is built on top of a modular architecture, allowing developers to easily extend and customize the functionality to meet their specific needs.

## Tech Stack
The Unitree Robot SDK Version 2 is built using a range of technologies, including:
* **C++**: The primary programming language used for the SDK
* **Eigen**: A high-level library for linear algebra and matrix operations
* **Boost**: A collection of reusable and portable C++ libraries
* **CMake**: A cross-platform build system generator
* **GCC**: A compiler for building and debugging the SDK
* **libyaml-cpp**: A YAML parser and emitter for C++
* **libeigen3**: A linear algebra library for C++
* **libboost-all**: A collection of reusable and portable C++ libraries
* **libspdlog**: A fast and flexible logging library for C++
* **libfmt**: A modern formatting library for C++

## Installation and Startup
To install and start using the Unitree Robot SDK Version 2, follow these steps:
### Prebuild Environment
* OS: Ubuntu 20.04 LTS
* CPU: aarch64 and x86_64
* Compiler: gcc version 9.4.0

### Environment Setup
Before building or running the SDK, ensure the following dependencies are installed:
* CMake (version 3.10 or higher)
* GCC (version 9.4.0)
* Make

You can install the required packages on Ubuntu 20.04 with:
```bash
apt-get update
apt-get install -y cmake g++ build-essential libyaml-cpp-dev libeigen3-dev libboost-all-dev libspdlog-dev libfmt-dev
```

### Build Examples
To build the examples inside this repository:
```bash
mkdir build
cd build
cmake ..
make
```

### Installation
To build your own application with the SDK, you can install the unitree_sdk2 to your system directory:
```bash
mkdir build
cd build
cmake ..
sudo make install
```
Or install unitree_sdk2 to a specified directory:
```bash
mkdir build
cd build
cmake .. -DCMAKE_INSTALL_PREFIX=/opt/unitree_robotics
sudo make install
```

## Basic Usage
The Unitree Robot SDK Version 2 provides a range of APIs and examples to help developers get started with building their own applications. For example, the `example/cmake_sample` directory provides a sample CMake project that demonstrates how to import the unitree_sdk2 into your CMake project.

## Contributing
The Unitree Robot SDK Version 2 is an open-source project, and we welcome contributions from the community. To contribute to the project, please fork the repository and submit a pull request with your changes. Please ensure that your code is formatted according to the project's coding standards and that all tests pass before submitting your pull request.

## Licensing
The Unitree Robot SDK Version 2 is licensed under the [MIT License](https://opensource.org/licenses/MIT). By contributing to the project, you agree to release your contributions under the MIT License.