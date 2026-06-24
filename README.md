# storm-wing
ESP32 remote controlled drone. With a DIY 3D printed chassis, made from the ground up.

## Building with vcpkg

Use the configure preset that matches your compiler family:

- `gcc-windows` for MinGW, which restores packages with the `x64-mingw-dynamic` triplet
- `msvc-windows` for Visual Studio/MSVC, which uses the standard `x64-windows` triplet
or
- `system-default` not specifying anything and letting the system default be applied

If you change compilers or triplets, clear the existing `build/` folder first so CMake and vcpkg do not reuse the previous triplet cache.
