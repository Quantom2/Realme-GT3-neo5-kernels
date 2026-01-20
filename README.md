[English](README.md) | [简体中文](README_CN.md) |
# Realme GT neo5 custom kernels

## WARNING: Your warranty is no longer valid!

I am **not responsible** for bricked devices, damaged hardware, or any issues that arise from using this kernel.

**Please** do thorough research and fully understand the features included in this kernel before flashing it!

By flashing this kernel, **YOU** are choosing to make these modifications. If something goes wrong, **do not blame me**!

### Proceed at your own risk!

---

# Features common for all variants
  - **KernelSU**: KernelSU is a root solution for Android GKI devices, it works in kernel mode and grants root permission to userspace applications directly in kernel space.
  - **SUSFS**: An addon root hiding kernel patches and userspace module for KernelSU.
  - Latest Realme GT neo5 sources
  - Latest SUSFS ඞ variants for all root solutions
  - LZ4KD ZRAM Patch Built-in
  - Ptrace Patch Built-in
  - Sultan Memory Patch Built-in
  - IPSet Support for Advanced Network Filtering
  - Wireguard Support
  - BBR v1 Support
  - BBG (Baseband-guard)️

### Features that unique for all versions
| --- \ --- | Stock | KernelSU | KernelSU SUSFS | KernelSU-Next | KernelSU-Next SUSFS | Wild KSU | Wild KSU SUSFS | Suki-SU Ultra SUSFS |
|----|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|
| Root | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| SUSFS | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ | ✅ | ✅ |
| Hooks | ❌ | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | [Kprobe](https://sukisu.org/guide/installation#method-3-manual-kernel-integration-advanced) |

---

# Installation instructions: 

Follow the steps for GKI:  
[Installation](https://kernelsu.org/guide/installation.html)

To get boot.img format:  
[Get My Kernel Format](https://github.com/TheWildJames/Get_My_Kernel_Format)

---

# Credits

- **KernelSU**: Developed by [tiann](https://github.com/tiann/KernelSU).
- **KernelSU-Next**: Developed by [rifsxd](https://github.com/KernelSU-Next/KernelSU-Next).
- **Magic-KSU**: Developed by [5ec1cff](https://github.com/5ec1cff/KernelSU).  
- **SUSFS**: Developed by [simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git).
- **SUSFS Module**: Developed by [sidex15](https://github.com/sidex15).
- **Sultan Kernels**: Developed by [kerneltoast](https://github.com/kerneltoast).
- **Wild Kernels**: Developed by [TheWildJames](https://github.com/TheWildJames).

Special thanks to the open-source community for their contributions!

---

# Support

If you encounter any issues or need help, feel free to open an issue in this repository or reach out to me.

---

# Disclaimer

Flashing this kernel will void your warranty, and there is always a risk of bricking your device. Please make sure to back up your data and ensure you understand the risks before proceeding.

**Proceed at your own risk!**

---

# Special thanks to the following people for their contributions!
This helps me alot! <3

[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) - Created SUSFS!  
[sidex15](https://github.com/sidex15) - Created module!  

If you have contributed and are not here please remind me!
