QUVNTNM TOOLCHAIN
===================================================
This toolchain is optimized for:
- ARMv7-a architecture (-march=armv7-a)
- Cortex A9 CPU (-mcpu=cortex-a9 -mtune=cortex-a9)
- NEON FPU (-mfpu=neon)
- Hard-float ABI (-mfloat-abi=hard)
- Linux Kernel 3.2.X

This toolchain uses:
- System zlib
- Linaro GCC 4.9.X (latest)
- OPENMP support
- Latest binutils/etc
- Other components specified in ".config" file
