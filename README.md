### Introduction

The concurrent overlap of GPU computation and the transfer of memory to and from the GPU can drastically improve the performance of CUDA applications. In this workshop you will learn to utilize CUDA Streams to perform copy/compute overlap in CUDA C++ applications by:

• Learning the rules and syntax governing the use of concurrent CUDA Streams
• Refactoring and optimizing an existing CUDA C++ application to perform copy/compute overlap

Upon completion, you will be able to build robust and efficient CUDA C++ applications that can leverage copy/compute overlap for significant performance gains.

### Learning Objectives

Learning the rules and syntax governing the use of concurrent CUDA Streams.
Refactoring and optimizing an existing CUDA C++ application to perform copy/compute overlap.


### The goals and core techniques
JupyterLab: Orient to the JupyterLab environment used for the interactive portions of the course
Application Overview: Become familiar with the CUDA C++ application you will be refactoring to use concurrent streams
Nsight Systems Setup: Launch and familiarize yourself with Nsight Systems, the application profiling tool you will be using to track application performance improvements in the course
CUDA Streams: Get an introducton to concurrent CUDA streams and the rules governing their behavior
Kernel Launches in Non-Default Streams: Practice launching CUDA kernels in concurrent streams
Memory Copies in Non-Default Streams: Practice performing asynchronous host-to-device and device-to-host memory transfers in concurrent streams
Considerations for Copy/Compute Overlap: Learn data chunking and indexing strategies in supportive of performing copy/compute overlap using concurrent streams
Perform Copy/Compute Overlap: Apply what you've learned to refactor a CUDA C++ application to utilize copy/compute overlap using concurrent streams
Conclusion: Review everything you've learned in the workshop
