
# Realme GT neo5 사용자 정의 커널

## 경고: 보증서가 더 이상 유효하지 않습니다!

이 커널 사용으로 인해 장치가 벽돌이 되거나, 하드웨어가 손상되거나, 기타 문제가 발생해도 저는 **책임지지 않습니다**.

**반드시** 이 커널에 포함된 기능을 충분히 연구하고 완전히 이해한 후 플래시하세요!

이 커널을 플래시함으로써 **귀하**는 이러한 수정 작업을 수행하기로 선택한 것입니다. 문제가 발생하면 **제자를 탓하지 마세요**!

### 자신의 위험에 책임세요!

---

# 모든 변형 공통 기능
  - **KernelSU**: KernelSU는 Android GKI 기기용 root 솔루션으로, 커널 모드에서 작동하며 root 권한을 직접 커널 공간에서 사용자 공간 애플리케이션에 부여합니다.
  - **SUSFS**: KernelSU용 루트 숨기 커널 패치 및 사용자 공간 모듈 애드온.
  - 최신 Realme GT neo5 소스 코드
  - 모든 root 솔루션용 최신 SUSFS ඞ 변형
  - 내장 LZ4KD ZRAM 패치
  - 내장 Ptrace 패치
  - 내장 Sultan Memory 패치
  - 고급 네트워크 필터링용 IPSet 지원
  - Wireguard 지원
  - BBR v1 지원
  - BBG (Baseband-guard)️

### 모든 버전에 고유한 기능
| --- \ --- | Stock | KernelSU | KernelSU SUSFS | KernelSU-Next | KernelSU-Next SUSFS | Wild KSU | Wild KSU SUSFS | Suki-SU Ultra SUSFS |
|----|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|
| Root | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| SUSFS | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ | ✅ | ✅ |
| Hooks | ❌ | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | [Kprobe](https://sukisu.org/guide/installation#method-3-manual-kernel-integration-advanced) |

---

# 설치 지침:

GKI 단계를 따르세요:
[설치](https://kernelsu.org/guide/installation.html)

boot.img 형식 얻기:
[내 커널 형식 얻기](https://github.com/TheWildJames/Get_My_Kernel_Format)

---

#  credits

- **KernelSU**: [tiann](https://github.com/tiann/KernelSU)이 개발.
- **KernelSU-Next**: [rifsxd](https://github.com/KernelSU-Next/KernelSU-Next)이 개발.
- **Magic-KSU**: [5ec1cff](https://github.com/5ec1cff/KernelSU)이 개발.
- **SUSFS**: [simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git)이 개발.
- **SUSFS 모듈**: [sidex15](https://github.com/sidex15)이 개발.
- **Sultan 커널**: [kerneltoast](https://github.com/kerneltoast)이 개발.
- **Wild 커널**: [TheWildJames](https://github.com/TheWildJames)이 개발.

오픈소스 커뮤니티의 기여에 감사드립니다!

---

# 지원

문제가 발생하거나 도움이 필요하면 이 저장소에서 issue를 열거나 저에게 연락하세요.

---

# 면책 조항

이 커널을 플래시하면 보증이 무효화되며 장치가 벽돌이 될 위험이 항상 있습니다. 계속하기 전에 데이터를 백업하고 위험을 이해하고 있는지 확인하세요.

**자신의 위험에 책임세요!**

---

# 다음 분들께 특별한 감사를 드립니다!
이것은 저에게 많이 도움이 됩니다! <3

[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) - SUSFS를 창조했습니다!
[sidex15](https://github.com/sidex15) - 모듈을 창조했습니다!

기여했지만 여기에 없다면 저에게 알려주세요!