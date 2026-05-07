emscripten-simd-playground
==========================
[emscripten/test/sse at main · emscripten-core/emscripten](https://github.com/emscripten-core/emscripten/tree/main/test/sse)

### Architectures
- ARM
  - [ARM intrinsics | Microsoft Learn](https://learn.microsoft.com/en-us/cpp/intrinsics/arm-intrinsics?view=msvc-170)
  - [ARM64 intrinsics | Microsoft Learn](https://learn.microsoft.com/en-us/cpp/intrinsics/arm64-intrinsics?view=msvc-170)
  - ```
    #include <arm_neon.h>                // Include the header
    uint8x16_t v = vdupq_n_u8(1);       // Example: Initialize NEON register
    ```
- x64
  - [x64 (amd64) intrinsics list | Microsoft Learn](https://learn.microsoft.com/en-us/cpp/intrinsics/x64-amd64-intrinsics-list?view=msvc-170)
    
### Tutorials
- [Using SIMD with WebAssembly — Emscripten 5.0.8-git (dev) documentation](https://emscripten.org/docs/porting/simd.html)

### Specification
- [WebAssembly/simd: Branch of the spec repo scoped to discussion of SIMD in WebAssembly](https://github.com/webassembly/simd/)

### Third-party libraries
- [yuikns/intrin: Compatibility <intrin.h> header for GCC](https://github.com/yuikns/intrin)
