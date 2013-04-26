ComputeUnity
============

ComputeUnity is a framework for creating and executing near identical code on multiple compute API platforms. These will potentially include GLSL, OpenCL, CUDA, Native CPU. No special language needs to be understood but a common GLSL style set of functions are supported and can be ran across each architecture with near to no change of codes.

Key features:
- Write code once, run anywhere
- Write in standard C language
- Runs as native compiled code for the target API platform (i.e. no special interpreted/meta languages)


TODOS:
 - Make some inital tests
 - Could have a choice of C/GLSL/CUDA style types/constructs so existing code on one platform may be ran on the alternative platform with ease
