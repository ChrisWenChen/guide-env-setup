# 多体计算研究环境搭建指南

这是一份专门为即将开始系统学习量子多体系统的数值计算（也许对别的领域也有参考价值！）的同学们准备的手把手环境配置攻略。无论你使用的是macOS、Windows、Linux还是WSL（Windows Subsystem for Linux），本指南都将帮助你从零开始搭建高效、完整的科研环境。

我们不仅覆盖核心计算工具链——Python、Julia、Fortran/C/C++、MPI、BLAS/LAPACK（包括OpenBlas/MKL）、PETSc/SLEPc，还精心整理了科研日常必备工具：网盘同步、文献管理（Zotero）、版本控制（Git）、终端优化等，让你的科研工作事半功倍。

所有示例代码均已通过测试，并托管在 GitHub 仓库 [[
guide-env-setup](https://github.com/ChrisWenChen/guide-env-setup)/codes/] 中，你可以随时下载验证或参考。

---

**作者**：{{ extra.author }} · **邮箱**：{{ extra.email }} · **版本**：{{ extra.version }} ({{ extra.release_date }})