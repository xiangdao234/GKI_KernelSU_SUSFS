# GKI KernelSU SUSFS
使用github Action自动构建 GKI 内核 （中文/[ENGLISH](README-EN.md)）
> 目前不支持一加 ColorOS14、15，刷入后可能需要清除数据开机。

尝试构建集成 [hymo 挂载元模块](https://github.com/Anatdx/hymo) 的 GKI 内核，但该项目目前仅支持 6.6，因此未完整合并到本仓库主分支。
参考发布：[hymo+gki](https://github.com/zzh20188/GKI_KernelSU_SUSFS/releases/tag/v2.0.0-r24)


预构建取消补丁，请直接使用[Unicode零宽修复模块](https://t.me/real5ec1cff/268) Xp模块

## SUKISU 之外的KernelSU？
几乎都不再使用SUSFS，甚至GKI，兼容性难以保证。
因此在本项目中均使用无SUSFS的GKI。


## 文档与指南

详细说明已整理到 [GitHub Wiki（中英双语）](https://github.com/zzh20188/GKI_KernelSU_SUSFS/wiki)，请优先查阅

[更新记录：doc/CHANGELOG.md](doc/CHANGELOG.md)

Wiki 包含：下载与刷写、无限重启处理、BUG 反馈指引、Tips、KSU 管理器与 SUSFS 模块、内核构建时间、紧急救援指南、内核版本兼容性说明等内容。

## KernelSU安装后 ...
> 此处更新安装后的玩法/实用软件/模块的List，均为官方渠道，排名不分先后
### 模块
1. LSPosed-Irena
    * [LSPosed-Irena仓库](https://github.com/re-zero001/LSPosed-Irena)
    * [LSPosed-Irena频道](https://t.me/lsposed_irena)
2. Zygisk Next/TrickyStore
    * [Zygisk Next仓库](https://github.com/Dr-TSNG/ZygiskNext)
    * [TrickyStore仓库](https://github.com/5ec1cff/TrickyStore)
    * [Zygisk Next/TrickyStore共频道](https://t.me/real5ec1cff)
### Xp模块
1. FuseFixer.apk
    * [Unicode零宽修复模块](https://t.me/real5ec1cff/268)

### 待完善...

