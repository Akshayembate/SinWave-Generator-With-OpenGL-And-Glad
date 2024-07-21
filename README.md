# OpenGL Graph Renderer

This project demonstrates how to create a simple graph using OpenGL and GLFW. It includes shaders for rendering the graph and handles basic input to close the application.

## Features

- Render a 2D graph with two sets of values
- Basic input handling to close the application

## Requirements

- OpenGL
- GLFW
- GLAD

## Getting Started

### Prerequisites

- Make sure you have the required libraries installed:
  - OpenGL
  - GLFW
  - GLAD

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourproject.git
2 . Navigate to the project directory:
  cd yourproject
3. Compile the project using your preferred C++ compiler. For example, using g++:
  g++ main.cpp -o graph_renderer -lglfw -ldl -lGL -lGLU
Running the Application
Run the compiled executable:
./graph_renderer
Code Overview
Shaders
vertexShaderSource: Vertex shader for rendering the graph.
fragmentShaderSource: Fragment shader for rendering the graph.
Functions
framebuffer_size_callback: Adjusts the viewport when the window size changes.
processInput: Handles user input.
checkOpenGLError: Checks for OpenGL errors and outputs them to the console.
compileShader: Compiles a shader from source code.
createShaderProgram: Links vertex and fragment shaders into a shader program.
renderGraph: Renders the graph using the provided data.
Main Function
Initializes GLFW and creates a window.
Sets up OpenGL context and loads GLAD.
Compiles and links shaders.
Sets up vertex data and buffers.
Enters the render loop, which:
Processes input
Clears the screen
Renders the graph
Swaps buffers and polls for events
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
GLFW
GLAD


Feel free to adjust the installation and running instructions according to your specific environment and requirements. Let me know if you need any further modifications or additions!

