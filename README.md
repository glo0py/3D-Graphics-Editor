3D Graphics Editor
An interactive 3D graphics editor developed in C++ with OpenGL, GLFW, and Dear ImGui. The project provides a graphical workspace for creating, importing, editing, and rendering 3D scenes.
Features
- Create and manipulate 3D primitives and custom geometry
- Apply position, rotation, and scaling transformations
- Adjust materials, lighting, and textures
- Import 3D geometry and work with scene data
- Interactive camera controls and real-time OpenGL rendering
- Additional graphics systems in the codebase, including animation, ray tracing, and particle simulation
Technology
C++ · OpenGL · GLFW · GLM · Dear ImGui · Make
Building
See [BUILDING.md](BUILDING.md) for platform-specific setup and dependencies.

On Ubuntu/Debian:
sudo apt update
sudo apt install -y build-essential libglfw3-dev libglm-dev libgl1-mesa-dev zenity
make
./editor
Structure
- src/ — implementation files
- include/ — headers and bundled library interfaces
- data/ — models, textures, and other scene resources
- tests/ — graphics and functionality tests
- main.cpp — program entry point
- Makefile — build configuration
Note
This repository documents a graphics editor project developed as coursework. It contains both editor framework code and project-specific implementations. See individual files for details.
