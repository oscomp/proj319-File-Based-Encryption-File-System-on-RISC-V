# proj319-File-Based-Encryption-File-System-on-RISC-V
# 支持 RISC-V 架构的文件级加密文件系统

## 项目描述

该项目目标结合版本管理和数据加密的设计，提供一种安全、可追踪的文件存系统。

随着数据安全问题的日益显著，数据加密越来越成为操作系统的基础机制。传统的文件系统级别的加密机制普遍采用全磁盘加密技术，虽然对磁盘上的数据安全提供的基础的整体加密保护，但难以满足不同文件的不同安全需求。

文件级加密可以支持不同文件采用不同的密钥加密，能够更好地满足用户对不同数据的安全诉求，也避免一个的泄漏造成所有数据泄漏的发生。

RISC-V 架构的芯片的安全模块与文件级加密文件系统的结合也能够更好的保障用户的数据安全。

## 预期目标

- 设计实现一个支持 RISC-V 架构的文件级加密文件系统

## 特征

- 支持基础的 POSIX 文件 IO 接口
- 文档、代码、问题、答疑交互过程都开放和开源的
- 能够运行在 openEuler RISC-V 版本上，并运行在 LicheePi4A 等典型的 RISC-V 开发板上

## 已有参考资料
- [ecryptfs](https://www.ecryptfs.org)
- [openEuler RISC-V](https://gitee.com/openeuler/RISC-V)

## 赛题分类
文件系统

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

高等

## License

Mulan PSL v2 license

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

- 姓名：余忠广
- 单位：中国科学院软件研究所
- Github ID：[https://github.com/zhongguang-iscas](https://github.com/zhongguang-iscas)
- Email：[zhongguang@iscas.ac.cn](mailto:zhongguang@iscas.ac.cn)
