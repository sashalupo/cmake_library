# CMake Library Project

## Overview
This project is a CMake-based library designed to demonstrate the use of CMake for building and managing C++ projects. The purpose of this project is to explain how to link an external library to an application.

## Features
- Modular C++ library
- CMake build system
- Cross-platform support

## Requirements
- CMake 3.10 or higher
- C++11 or higher
- A compatible C++ compiler (e.g., GCC, Clang, MSVC)

## Building the Project

### Building the Library
1. Create a build directory and navigate into it:
    ```sh
    mkdir build
    cd build
    ```

2. Run CMake to configure the project:
    ```sh
    cmake ..
    ```

3. Build the library:
    ```sh
    make
    ```

4. Install the library:
    ```sh
    make install
    ```

### Building the `foo_project`
1. Navigate to the `foo_project` directory:
    ```sh
    cd ../foo_project
    ```

2. Create a build directory and navigate into it:
    ```sh
    mkdir build
    cd build
    ```

3. Run CMake to configure the project:
    ```sh
    cmake ..
    ```

4. Build the project:
    ```sh
    make
    ```

## Usage
After building the project, you can use the library in your own projects by linking against it. Include the appropriate headers and link the compiled library.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
