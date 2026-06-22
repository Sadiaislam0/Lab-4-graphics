# Lab-4
# Author
# Sadia Islam
# Description
This program creates an OpenGL window that displays a single triangle. Initially, the triangle is colored cyan and smoothly transitions to magenta over time using animation. The program also includes interactive keyboard controls to modify the triangle’s color and behavior dynamically.
Language & Tools
 Language: C++
 Graphics Library: OpenGL (GLFW + GLAD)
 Editor: VS Code
 Operating System: Windows OS
How to Compile and Run
1. Open the terminal in the project folder.
2. Compile the program: ⁠g++ main.cpp -o main -lglfw -lopengl32 -lglad⁠
3. Run the program: ⁠./main⁠
Key Functionality
1. Triangle Behavior
 Initial color: Cyan
 Animation: Gradually transitions from Cyan → Magenta.
2. Keyboard Controls
 Press 'W': Triangle becomes White while holding the key. When released, animation resumes.
 Press 'R': Triangle becomes Red permanently. Animation stops and does not resume.
 Press 'S': (First letter of name) Closes the window.
3. Window Settings
 Window title: 0432320005101054
 Display: Single animated triangle.
Proof of Execution
The output screenshot with VS Code terminal and OpenGL window is attached in the classroom submission.
