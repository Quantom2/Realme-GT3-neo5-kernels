
# Realme GT neo5 自定义内核

## 警告：您的保修将失效！

我**不负责**因使用此内核而导致的设备变砖、硬件损坏或任何问题。

**请**在刷入此内核前进行充分的研究并完全理解其中包含的功能！

通过刷入此内核，**您**选择进行这些修改。如果出现问题，**不要责怪我**！

### 风险自负！

---

# 所有变体的共同特性
  - **KernelSU**：KernelSU 是 Android GKI 设备的 root 解决方案，它在内核模式下工作，直接在内核空间中向用户空间应用授予 root 权限。
  - **SUSFS**：KernelSU 的根隐藏内核补丁和用户空间模块的附加组件。
  - 最新的 Realme GT neo5 源代码
  - 所有 root 解决方案的最新 SUSFS ඞ 变体
  - 内置 LZ4KD ZRAM 补丁
  - 内置 Ptrace 补丁
  - 内置 Sultan 内存补丁
  - 用于高级网络过滤的 IPSet 支持
  - Wireguard 支持
  - BBR v1 支持
  - BBG (Baseband-guard)️

### 所有版本的独特功能
| --- \ --- | Stock | KernelSU | KernelSU SUSFS | KernelSU-Next | KernelSU-Next SUSFS | Wild KSU | Wild KSU SUSFS | Suki-SU Ultra SUSFS |
|----|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|
| Root | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| SUSFS | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ | ✅ | ✅ |
| Hooks | ❌ | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | [Kprobe](https://sukisu.org/guide/installation#method-3-manual-kernel-integration-advanced) |

---

# 安装说明：

按照 GKI 的步骤操作：
[安装](https://kernelsu.org/guide/installation.html)

获取 boot.img 格式：
[获取我的内核格式](https://github.com/TheWildJames/Get_My_Kernel_Format)

---

#  credits

- **KernelSU**：由 [tiann](https://github.com/tiann/KernelSU) 开发。
- **KernelSU-Next**：由 [rifsxd](https://github.com/KernelSU-Next/KernelSU-Next) 开发。
- **Magic-KSU**：由 [5ec1cff](https://github.com/5ec1cff/KernelSU) 开发。
- **SUSFS**：由 [simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) 开发。
- **SUSFS 模块**：由 [sidex15](https://github.com/sidex15) 开发。
- **Sultan 内核**：由 [kerneltoast](https://github.com/kerneltoast) 开发。
- **Wild 内核**：由 [TheWildJames](https://github.com/TheWildJames) 开发。

特别感谢开源社区的贡献！

---

# 支持

如果您遇到任何问题或需要帮助，请随时在此存储库中打开 issue 或与我联系。

---

# 免责声明

刷入此内核将使您的保修失效，并且始终存在设备变砖的风险。请确保备份您的数据，并确保在继续之前了解风险。

**风险自负！**

---

# 特别感谢以下人员的贡献！
这对我帮助很大！ <3

[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) - 创建了 SUSFS！
[sidex15](https://github.com/sidex15) - 创建了模块！

如果您有贡献但未在此列出，请提醒我！