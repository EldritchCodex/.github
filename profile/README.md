# Project Description
The **EldritchCodex** is a learning project from [RenanBomtempo](https://github.com/renanbomtempo) that explores the software engineering, architecture and applied mathematics behind the development of computer graphics and physics simulations software for both entertainment and scientific applications.

The project's goal is to develop several modular tools that can all integrate with a central core framework, following a Host-Plugin architecture.

The core is **[Nodens](https://github.com/eldritchcodex/nodens)**, and it handles:

- application interactive loop, 
- pub/sub event system, 
- multi-threaded job system,
- cross-platflorm window and input management (GLFW),
- logging (spdlog),
- immediate mode GUI (ImGUI).

The currently planned plugins are:
- **[Nyar](https://github.com/eldritchcodex/nyar)**: a Vulkan-based real-time renderer.
- **Azath**: a multi-physics engine.
- **Tindalos**: an offline ray-tracer.

# Main References
- Akenine-Möller, T., Haines, E., Hoffman, N., Pesce, A., Iwanicki, M., & Hillaire, S. (2019). **Real-time rendering** (Fourth edition, first issued in hardback). CRC Press.
- Angel, E., & Shreiner, D. (2012). **Interactive computer graphics: A top-down approach with shader-based OpenGL** (6th ed). Addison-Wesley.
- Castorina, M., & Sassone, G. (2023). **Mastering graphics programming with vulkan: Develop a modern rendering engine from first principles to state-of-the-art techniques**. Packt Publishing.
- Eisemann, E. (Ed.). (2012). **Real-time shadows**. CRC Press.
- Gregory, J. (2019). **Game engine architecture** (Third edition). CRC Press, Taylor & Francis Group.
- Haines, E., & Akenine-Möller, T. (Eds.). (2019). **Ray Tracing Gems: High-Quality and Real-Time Rendering with DXR and Other APIs**. Apress. https://doi.org/10.1007/978-1-4842-4427-2
- Horton, I., & Van Weert, P. (2023). **Beginning C++23: From Beginner to Pro**. Apress. https://doi.org/10.1007/978-1-4842-9343-0
- Hughes, J. F. (2014). **Computer Graphics: Principles and Practice**. Addison-Wesley.
- Lengyel, E. (2016). **Foundations of game engine development. Volume 1: Mathematics**. Terathon Software LLC.
- Lengyel, E. (2019). **Foundations of game engine development. Volume 2: Rendering**. Terathon Software LLC.
- Malhotra, D., & Malhotra, N. (2024). **Data structures and program design using C++: A self-teaching introduction**. Packt Publishing.
- Marrs, A., Shirley, P., & Wald, I. (Eds.). (2021). **Ray Tracing Gems II: Next Generation Real-Time Rendering with DXR, Vulkan, and OptiX. Apress**. https://doi.org/10.1007/978-1-4842-7185-8
- The Cherno. (n.d.). **Game Engine Series**. YouTube. Retrieved November 23, 2025, from http://www.youtube.com/playlist?list=PLlrATfBNZ98dC-V-N3m0Go4deliWHPFwT

---

> "For beyond the veil of our limited understanding there lies an arcane ballet of unseen dimensions."
