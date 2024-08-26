# Yet Another Build \[System\]

This small program allows to make ninja build files using ruby

Goal of this project is to be light-weight and modifiable

## Why other tools are not suitable sometimes?
1. When it comes to multi-language projects with compex dependencies it may be needed to glob. Most modern build tools consider it to be a bad practice, and it is, unless you need to build third-party code with random buildsystem and it won't be modified much, so "globbing" problem doesn't really matter
2. "Declarative" build systems don't provide capabilities comparable to CMake: it's the worst build system except that there are no better solutions (ok, maybe Gradle). And CMake language is extremely inconvenient.
