[English](README.md) | [简体中文](README_CN.md) | 
# Realme GT Neo5 定制内核

## ⚠️ 警告：您的保修将立即失效！

对于因使用本内核导致的设备变砖、硬件损坏或任何其他问题，**本人概不负责**。

**请务必**在刷入本内核前进行充分研究，并完全理解其包含的所有功能！

刷入本内核意味着**您**自愿进行这些修改。若出现问题，**切勿归咎于我**！

### 后果自负！

---

# 所有版本通用功能
  - **KernelSU**：适用于 Android GKI 设备的 Root 解决方案，在内核模式下运行，直接在内核空间为用户空间应用程序授予 Root 权限。
  - **SUSFS**：一个用于 KernelSU 的 Root 隐藏内核补丁和用户空间模块。
  - 基于最新的 Realme GT Neo5 源码构建
  - 适用于所有 Root 解决方案的最新 SUSFS ඞ 变体
  - 内置 LZ4KD ZRAM 补丁
  - 内置 Ptrace 补丁
  - 内置 Sultan 内存补丁
  - 支持 IPSet 实现高级网络过滤
  - 支持 Wireguard
  - 支持 BBR v1
  - 支持 BBG (Baseband-guard)️

### 各版本独有功能对比
| 版本 \ Root 方案 | 原版 (Stock) | KernelSU | KernelSU SUSFS | KernelSU-Next | KernelSU-Next SUSFS | Wild KSU | Wild KSU SUSFS | Suki-SU Ultra SUSFS |
| :-------------- | :---------: | :------: | :-----------: | :----------: | :----------------: | :------: | :-----------: | :----------------: |
| Root            |     ❌      |    ✅     |      ✅       |      ✅       |        ✅         |    ✅    |      ✅       |        ✅         |
| SUSFS           |     ❌      |    ❌     |      ✅       |      ❌       |        ✅         |    ❌    |      ✅       |        ✅         |
| Hooks           |     ❌      | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | 手动 Hooks v1.4 | 手动 Hooks v1.4 | 手动 Hooks v1.4 | 手动 Hooks v1.4 | [Kprobe](https://sukisu.org/guide/installation#method-3-manual-kernel-integration-advanced) |

---

# 安装说明

请遵循 GKI 设备的安装步骤：
[安装指南](https://kernelsu.org/guide/installation.html)

获取 boot.img 格式文件：
[获取我的内核格式](https://github.com/TheWildJames/Get_My_Kernel_Format)

---

# 致谢

- **KernelSU**：由 [tiann](https://github.com/tiann/KernelSU) 开发。
- **KernelSU-Next**：由 [rifsxd](https://github.com/KernelSU-Next/KernelSU-Next) 开发。
- **Magic-KSU**：由 [5ec1cff](https://github.com/5ec1cff/KernelSU) 开发。 *(注：原文此处链接指向 KernelSU 主项目，Magic-KSU 可能是其分支或特定版本)*
- **SUSFS**：由 [simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) 开发。
- **SUSFS 模块**：由 [sidex15](https://github.com/sidex15) 开发。
- **Sultan Kernels**：由 [kerneltoast](https://github.com/kerneltoast) 开发。
- **Wild Kernels**：由 [TheWildJames](https://github.com/TheWildJames) 开发。

特别感谢开源社区成员的贡献！

---

# 支持

如果您遇到任何问题或需要帮助，欢迎在此仓库提交 Issue 或联系我。

---

# 免责声明

刷入本内核将使您的保修失效，并且存在设备变砖的风险。请务必备份数据，并在操作前确保您充分了解相关风险。

**后果自负！**

---

# 特别感谢以下贡献者！
你们的帮助对我至关重要！<3

[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) - 创建了 SUSFS！
[sidex15](https://github.com/sidex15) - 创建了模块！

如果您有贡献但未在此列出，请提醒我！

---
