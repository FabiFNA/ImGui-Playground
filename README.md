# Dear ImGui + GLFW + OpenGL Beispielprojekt

Ein einfaches C++-Projekt, das [Dear ImGui](https://github.com/ocornut/imgui), [GLFW](https://www.glfw.org/), und OpenGL nutzt – entwickelt unter Linux mit `g++` und Visual Studio Code **ohne CMake**.

---

## 📦 Dependencies

The following packages are required to compile the code:

```bash
sudo apt update
sudo apt install g++ libglfw3-dev libgl1-mesa-dev
```

---

## Projectstructure

```
imgui-vscode-project/
│
├── main.cpp
├── imgui/              # ImGui Sourcecode
│   ├── imgui.cpp
│   ├── imgui.h
│   ├── imgui_demo.cpp
│   ├── imgui_draw.cpp
│   ├── imgui_tables.cpp
│   ├── imgui_widgets.cpp
│   └── backends/
│       ├── imgui_impl_glfw.cpp
│       ├── imgui_impl_glfw.h
│       ├── imgui_impl_opengl3.cpp
│       └── imgui_impl_opengl3.h
├── .vscode/
│   ├── tasks.json
│   └── c_cpp_properties.json
├── README.md
```
