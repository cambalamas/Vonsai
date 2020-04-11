# VONSAI Renderer

> A toy engine on top of **OpenGL4** using *C++17*.

<p align="center"> <img alt="Vonsai logo" src="./doc/images/Vonsai.png" height="250" width="250"> </p>

## Done
- [X] Allow multi-window with independent contexts
- [X] Input system exposed to the user *Unity-Like*
- [X] Lights loaded as UBO
- [X] Efficient UBO updating using glBufferSubData and caching with unordered_map
- [X] Cached uniforms locations.
- [X] BindGuard for ensure to un/bind a resource based on scope, following [RAII idiom](https://en.cppreference.com/w/cpp/language/raii).

## Work In Progress
- [ ] Material abstraction.
- [ ] Indirection layer for gpu render to allow the use of OpenGL, Vulkan, DX11/12 or Metal transparently.
- [ ] Indirection layer for windowing, allowing easy replace of GLFW in the future if it is desired.
- [ ] Add ASSIMP to support many data filetypes; *specially FBX, DAE, DXF, BVH and glTF*.
- [ ] _**E**ntitiy_ _**C**omponent_ _**S**ystem_; a.k.a. *Data oriented design*.

!["Three monkeys screenshot"](./doc/images/screenshot.png)
