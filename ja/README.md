
# Realme GT neo5 カスタムカーネル

## 警告：保証は無効になります！

このカーネルを使用导致的デバイスのbrick化、ハードウェアの損傷、または什么问题が発生しても、私は**責任を持ちません**。

**必ず**このカーネルに含まれている機能を十分に研究し、理解した上でフラッシュしてください！

このカーネルをフラッシュすることで、**あなた**はこれらの modification を行うことを選択したことになります。何か問題が発生した場合、**私を責めないでください**！

### リスクは自己責任です！

---

# すべてのバリアントに共通する機能
  - **KernelSU**：KernelSU は Android GKI デバイス向けの root ソリューションで、カーネルモードで動作し、root 権限を直接カーネル空間からユーザー空間アプリケーションに付与します。
  - **SUSFS**：KernelSU のルート非表示カーネルパッチとユーザー空間モジュール用のアドオン。
  - 最新の Realme GT neo5 ソースコード
  - すべての root ソリューション向けの最新の SUSFS ඞ バリアント
  - 組み込み LZ4KD ZRAM パッチ
  - 組み込み Ptrace パッチ
  - 組み込み Sultan Memory パッチ
  - 高度なネットワークフィルタリング用の IPSet サポート
  - Wireguard サポート
  - BBR v1 サポート
  - BBG (Baseband-guard)️

### すべてのバージョンに固有の機能
| --- \ --- | Stock | KernelSU | KernelSU SUSFS | KernelSU-Next | KernelSU-Next SUSFS | Wild KSU | Wild KSU SUSFS | Suki-SU Ultra SUSFS |
|----|----------------|----------------|----------------|----------------|----------------|----------------|----------------|----------------|
| Root | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| SUSFS | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ | ✅ | ✅ |
| Hooks | ❌ | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | [Kprobe](https://kernelsu.org/guide/how-to-integrate-for-non-gki.html#integrate-with-kprobe) | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | Manual hooks v1.4 | [Kprobe](https://sukisu.org/guide/installation#method-3-manual-kernel-integration-advanced) |

---

# インストール手順：

GKI の手順に従ってください：
[インストール](https://kernelsu.org/guide/installation.html)

boot.img 形式を取得：
[マイカーネル形式を取得](https://github.com/TheWildJames/Get_My_Kernel_Format)

---

#  credits

- **KernelSU**：[tiann](https://github.com/tiann/KernelSU) によって開発。
- **KernelSU-Next**：[rifsxd](https://github.com/KernelSU-Next/KernelSU-Next) によって開発。
- **Magic-KSU**：[5ec1cff](https://github.com/5ec1cff/KernelSU) によって開発。
- **SUSFS**：[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) によって開発。
- **SUSFS モジュール**：[sidex15](https://github.com/sidex15) によって開発。
- **Sultan カーネル**：[kerneltoast](https://github.com/kerneltoast) によって開発。
- **Wild カーネル**：[TheWildJames](https://github.com/TheWildJames) によって開発。

オープンソースコミュニティの貢献に感謝します！

---

# サポート

問題が発生した場合やヘルプが必要な場合は、このリポジトリで issue を開くか、私連絡してください。

---

# 免责声明

このカーネルをフラッシュすると保証が無効になり、デバイス brick 化のリスクが常にあります。続行する前にデータをバックアップし、リスクを理解していることを確認してください。

**リスクは自己責任です！**

---

# 以下の人々への特別な感謝！
これは私にとって大いに役立ちます！ <3

[simonpunk](https://gitlab.com/simonpunk/susfs4ksu.git) - SUSFS を作成！
[sidex15](https://github.com/sidex15) - モジュールを作成！

貢献したがここに载っていない場合は、私に思い出させてください！