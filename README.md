# STB Image
Basic [STB Image](https://github.com/nothings/stb.git) wrapper for CMake Projects.

## Install

Clone the repo and add the following to your CMakeLists.txt

```cmake
add_subdirectory(PATH/TO/STBI_REPO)

target_link_libraries(YOUR_TARGET stbi::stbi)
```

## Usage

```c++
// Include the respective header file
#include <stbi/stb_image.h>
```
