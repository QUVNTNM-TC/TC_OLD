QUVNTNM TOOLCHAIN
===================================================
This toolchain is optimized for:
- Generic architecture
- Cortex A15 CPU (-mcpu=cortex-a15 -mtune=cortex-a15)
- NEON VFPv4 FPU (-mfpu=neon-vfpv4)
- Hard-float ABI (-mfloat-abi=hard)
- Linux Kernel 3.4.X

This toolchain uses:
- System zlib
- Linaro GCC 4.9.X (latest)
- Latest binutils/etc
- Other components specified in ".config" file
