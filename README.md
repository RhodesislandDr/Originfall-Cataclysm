# Originfall-Cataclysm
A minecraft mod.A Corestone infection module designed based on the definitions of Corestone and the Corestone Project in Arknights Impact.
├── README.md                 新增：项目说明、目录结构、构建方法、r450 版本要点
├── build.gradle / settings.gradle / gradle.properties / .gitignore
├── libs/                     编译期依赖（仅保留构建脚本实际引用的三个版本）
│   ├── epic-fight-20-6.14.17-mc1.20.1-forge.jar
│   ├── l2hostility-2-14.5.19.jar
│   └── l2library-2-8.5.3.jar
└── src/
    ├── epicfight/            史诗战斗兼容层源码集（3 个文件）
    └── l2compat/             莱特兰-恶意兼容层源码集（1 个文件）
# 许可
Copyright (C) 2026 RhodesislandDr
# 源代码
本项目的源代码（`/src` 目录及构建脚本）采用GNU GPLv3发布。详见 `LICENSE`。
# 美术/音频/模型/动画等素材
本项目的素材（`/assets` 目录等）采用All Rights Reserved (ARR)。未经作者书面许可，任何人不得使用、复制、修改、分发或用于商业用途。详见 `LICENSE-ASSETS`。
代码包内不提供该项目美术/音频/模型/动画等素材，需使用者个人替换后使用。
本模组所有音乐均来自塞壬唱片MSR，使用协议为 CC BY-NC 4.0 。在模组内使用时基于原曲进行了节选。使用请联系著作权方获得许可。
# 再分发要求
当你分发基于本项目的衍生作品时：
- 源代码部分必须继续以 GPLv3 授权；
- 你必须移除或替换所有 ARR 素材，或获得版权持有人的单独许可；
- 不得将 ARR 素材作为 GPLv3 内容再分发。
