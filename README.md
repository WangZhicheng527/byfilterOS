byFilterOS

中文版本：

byFilterOS 是一个极简的、使用设备树（Devicetree）的嵌入式操作系统内核。它专为资源受限的嵌入式场景设计，同时保持足够的可扩展性以应用于实际产品中。

设计哲学：
byFilterOS 的设计灵感来源于电子电路中的旁路电容和去耦电容——它们的作用是滤除电源线上的干扰和杂波，让信号更加纯净。
同样地，byFilterOS 的目标是"旁路"掉传统操作系统的复杂性，像一个滤波器一样，只保留最纯净、最核心的功能。
它不为"大而全"而生，而是为那些希望在保持产品化能力的同时，拥有一个干净、可控、可移植内核的开发者而设计。

核心特性：
    - 极简设计：代码量小，结构清晰，易于理解和维护
    - 设备树支持：实现硬件描述与内核逻辑的解耦，大幅提升跨平台可移植性
    - 轻量高效：专为Flash和RAM资源有限的嵌入式环境优化
    - 可产品化：内核架构设计兼顾学习和实际产品部署需求

适用场景：
    - 资源受限的嵌入式设备（MCU级别）
    - 需要快速移植到不同硬件平台的项目
    - 追求代码透明度和可控性的产品开发
    - 操作系统内核原理的学习与研究

快速开始：
    环境要求：待补充
    构建：待补充
    运行：待补充

贡献：
欢迎提交 Bug 报告、功能建议或代码贡献。请阅读 CONTRIBUTING.md 了解如何参与。

许可证：
本项目采用 MIT License 开源许可证。
Copyright (c) 2026 Hefei Youyi Technology Co., Ltd.

联系方式：
    - 项目维护者：王志成 (WangZhicheng527)
    - 邮箱：royma1992@sina.com
    - 公司：合肥有仪科技有限公司 (Hefei Youyi Technology Co., Ltd.)


英文版本：

byFilterOS is a minimalist embedded operating system kernel with Devicetree support. It is designed for resource-constrained embedded scenarios while maintaining enough extensibility for real-world product deployment.

Design Philosophy:
The design of byFilterOS is inspired by bypass capacitors and decoupling capacitors in electronic circuits — they filter out noise and interference from power lines, leaving a cleaner signal.
Similarly, byFilterOS aims to "bypass" the complexity of traditional operating systems, acting like a filter that retains only the purest and most essential core functions.
It is not built for "everything under the sun", but for developers who want a clean, controllable, and portable kernel that balances learning with product-readiness.

Key Features:
    - Minimalist Design: Small codebase, clean structure, easy to understand and maintain
    - Devicetree Support: Decouples hardware description from kernel logic for excellent cross-platform portability
    - Lightweight & Efficient: Optimized for embedded environments with limited Flash and RAM
    - Product-Ready: Architecture designed for both learning and real-world product deployment

Use Cases:
    - Resource-constrained embedded devices (MCU-level)
    - Projects requiring rapid porting across different hardware platforms
    - Product development where code transparency and controllability are priorities
    - Learning and research on OS kernel internals

Quick Start:
    Prerequisites: TBD
    Build: TBD
    Run: TBD

Contributing:
We welcome bug reports, feature suggestions, and code contributions. Please read CONTRIBUTING.md to learn how to get involved.

License:
This project is open-sourced under the MIT License.
Copyright (c) 2026 Hefei Youyi Technology Co., Ltd.

Contact:
    - Maintainer: Wang Zhicheng (WangZhicheng527)
    - Email: royma1992@sina.com
    - Company: Hefei Youyi Technology Co., Ltd.
