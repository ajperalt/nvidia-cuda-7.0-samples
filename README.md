# nvidia-cuda-7.0-samples
CUDA Samples
1. Release Notes
This section describes the release notes for the CUDA Samples only. For the release notes for the whole CUDA Toolkit, please see CUDA Toolkit Release Notes.

1.1. CUDA 7.0
Removed support for Windows 32-bit builds.
The Makefile x86_64=1 and ARMv7=1 options have been deprecated. Please use TARGET_ARCH to set the targeted build architecture instead.
The Makefile GCC option has been deprecated. Please use HOST_COMPILER to set the host compiler instead.
The CUDA Samples are no longer shipped as prebuilt binaries on Windows. Please use VS Solution files provided to build respective executable.
Added 0_Simple/clock_nvrtc. Demonstrates how to compile clock function kernel at runtime using libNVRTC to measure the performance of kernel accurately.
Added 0_Simple/inlinePTX_nvrtc. Demonstrates compilation of CUDA kernel having PTX embedded at runtime using libNVRTC.
Added 0_Simple/matrixMul_nvrtc. Demonstrates compilation of matrix multiplication CUDA kernel at runtime using libNVRTC.
Added 0_Simple/simpleAssert_nvrtc. Demonstrates compilation of CUDA kernel having assert() at runtime using libNVRTC.
Added 0_Simple/simpleAtomicIntrinsics_nvrtc. Demonstrates compilation of CUDA kernel performing atomic operations at runtime using libNVRTC.
Added 0_Simple/simpleTemplates_nvrtc. Demonstrates compilation of templatized dynamically allocated shared memory arrays CUDA kernel at runtime using libNVRTC.
Added 0_Simple/simpleVoteIntrinsics_nvrtc. Demonstrates compilation of CUDA kernel which uses vote intrinsics at runtime using libNVRTC.
Added 0_Simple/vectorAdd_nvrtc. Demonstrates compilation of CUDA kernel performing vector addition at runtime using libNVRTC.
Added 4_Finance/binomialOptions_nvrtc. Demonstrates runtime compilation using libNVRTC of CUDA kernel which evaluates fair call price for a given set of European options under binomial model.
Added 4_Finance/BlackScholes_nvrtc. Demonstrates runtime compilation using libNVRTC of CUDA kernel which evaluates fair call and put prices for a given set of European options by Black-Scholes formula.
Added 4_Finance/quasirandomGenerator_nvrtc. Demonstrates runtime compilation using libNVRTC of CUDA kernel which implements Niederreiter Quasirandom Sequence Generator and Inverse Cumulative Normal Distribution functions for the generation of Standard Normal Distributions.


Read more at: http://docs.nvidia.com/cuda/cuda-samples/index.html#ixzz3dLzodJY7 
Follow us: @GPUComputing on Twitter | NVIDIA on Facebook
