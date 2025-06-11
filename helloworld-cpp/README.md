# Hello World C++ Project

This is a simple C++ project that demonstrates how to create a "Hello, World!" application using C++. 

## Project Structure

```
helloworld-cpp
├── src
│   └── main.cpp
├── CMakeLists.txt
└── README.md
```

## Requirements

- CMake
- A C++ compiler (e.g., g++, clang++)

## Building the Project

1. Open a terminal and navigate to the project directory.
2. Create a build directory:
   ```
   mkdir build
   cd build
   ```
3. Run CMake to configure the project:
   ```
   cmake ..
   ```
4. Build the project:
   ```
   cmake --build .
   ```

## Running the Application

After building the project, you can run the application with the following command:

```
./HelloWorld
```

You should see the output:

```
Hello, World!
``` 

## License

This project is licensed under the MIT License.