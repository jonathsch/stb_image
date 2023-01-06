# STB Image
Basic [STB Image](https://github.com/nothings/stb.git) wrapper for CMake Projects.

## Usage

Clone the repo and add the following to your CMakeLists.txt

```
add_subdirectory(stb)

target_link_libraries(YOUR_TARGET stb::stb)
```