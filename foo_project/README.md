# foo_project

This project is a simple C++ application that utilizes a custom library called `foo_lib`. 

## Project Structure

```
foo_project
├── src
│   ├── main.cpp          # Entry point of the application
│   └── foo_lib
│       ├── foo_lib.cpp   # Implementation of foo_lib functions
│       └── foo_lib.h     # Declaration of foo_lib functions and classes
├── CMakeLists.txt        # CMake configuration file
└── README.md             # Project documentation
```

## Building the Project

To build the project, follow these steps:

1. Ensure you have CMake installed on your system.
2. Open a terminal and navigate to the `foo_project` directory.
3. Create a build directory:
   ```
   mkdir build
   cd build
   ```
4. Run CMake to configure the project:
   ```
   cmake ..
   ```
5. Build the project:
   ```
   make
   ```

## Running the Executable

After building the project, you can run the executable with the following command:

```
./foo_project
```

## License

This project is licensed under the MIT License. See the LICENSE file for more details.