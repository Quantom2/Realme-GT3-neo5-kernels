
# Realme GT neo5 Özel Çekirdek

## UYARI: Garantiniz artık geçerli değil!

Bu çekirdeği kullanmaktan kaynaklanan brick olmuş cihazlar, hasar görmüş donanım veya diğer sorunlar için **sorumlu değilim**.

**Lütfen** bu çekirdeği flash etmeden önce dahil edilen özellikleri iyice araştırın ve tam olarak anlayın!

Bu çekirdeği flash ederek **siz** bu değişiklikleri yapmayı seçiyorsunuz. Bir şey yanlış giderse, **beni suçlamayın**!

### Kendi riskinizle devam edin!

---

# Tüm varyantlar için ortak özellikler
  - **KernelSU**: KernelSU, Android GKI cihazları için bir root çözümüdür, çekirdek modunda çalışır ve root yetkisini doğrudan çekirdek alanından kullanıcı alanı uygulamalarına verir.
  - **SUSFS**: KernelSU için kök gizleme çekirdek yamaları ve kullanıcı alanı modülü eklentisi.
  - En son Realme GT neo5 kaynak kodları
  - Tüm root çözümleri için en son SUSFS ඞ varyantları
  - Yerleşik LZ4KD ZRAM Yaması
  - Yerleşik Ptrace Yaması
  - Yerleşik Sultan Memory Yaması
  - Gelişmiş Ağ Filtreleme için IPSet Desteği
  - Wireguard Desteği
  - BBR v1 Desteği
  - BBG (Baseband-guard)️

### Tüm sürümler için benzersiz özellikler
| --- \ --- | Stock | KernelSU | KernelSU SUSFS | KernelSU-Next | KernelSU-Next SUSFS | Wild KSU | Wild KSU SUSFS | Suki-SU Ultra SUSFS |
|----|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|
| Root | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| SUSFS | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ | ✅ | ✅ |
| Hooks | ❌ | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | [Kprobe](https://sukisu.org/guide/installation#method-3-manual-kernel-integration-advanced) |

---

# Kurulum talimatları:

GKI adımlarını takip edin:
[Kurulum](https://kernelsu.org/guide/installation.html)

boot.img formatını almak için:
[Çekirdek Formatımı Al](https://github.com/TheWildJames/Get_My_Kernel_Format)

---

#  credits

- **KernelSU**: [tiann](https://github.com/tiann/KernelSU) tarafından geliştirildi.
- **KernelSU-Next**: [rifsxd](https://github.com/KernelSU-Next/KernelSU-Next) tarafından geliştirildi.
- **Magic-KSU**: [5ec1cff](https://github.com/5ec1cff/KernelSU) tarafından geliştirildi.
- **SUSFS**: [simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) tarafından geliştirildi.
- **SUSFS Modülü**: [sidex15](https://github.com/sidex15) tarafından geliştirildi.
- **Sultan Çekirdekleri**: [kerneltoast](https://github.com/kerneltoast) tarafından geliştirildi.
- **Wild Çekirdekler**: [TheWildJames](https://github.com/TheWildJames) tarafından geliştirildi.

Açık kaynak topluluğunun katkılarına özel teşekkürler!

---

# Destek

Sorun yaşarsanız veya yardıma ihtiyacınız olursa, bu depoda bir issue açmaktan veya benimle iletişime geçmekten çekinmeyin.

---

# Sorumluluk reddi

Bu çekirdeği flash etmek garantinizi geçersiz kılacak ve cihazınızın brick olma riski her zaman olacaktır. Devam etmeden önce verilerinizi yedeklediğinizden ve riskleri anladığınızdan emin olun.

**Kendi riskinizle devam edin!**

---

# Aşağıdaki kişilere özel teşekkürler!
Bu bana çok yardımcı oluyor! <3

[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) - SUSFS'yi oluşturdu!
[sidex15](https://github.com/sidex15) - Modülü oluşturdu!

Katkıda bulunduysanız ve burada yazmıyorsanız, lütfen bana hatırlatın!