# 来源与开发说明

本文件夹是 Codex 微信会话管家的作品展示材料，包含项目介绍、截图、架构示意、验证摘要及少量实际代码节选，不是完整安装包。

项目由本人提出需求、设计使用流程并反馈真实使用结果；代码实现、故障分析、测试与整理使用 Codex 辅助完成。

微信桥接层基于 [BigPizzaV3/CodexPlusPlus](https://github.com/BigPizzaV3/CodexPlusPlus) 的 [tools/codex-wechat/codex_wechat.py](https://github.com/BigPizzaV3/CodexPlusPlus/blob/main/tools/codex-wechat/codex_wechat.py) 修改。既有 iLink 登录、轮询与 Codex 后端骨架属于上游工作，不作为本作品从零独立开发的成果。

新增会话管理界面、状态与配置保护、归档恢复及桌面交接流程属于本项目改造范围。项目沿用 GNU AGPL v3，完整文本见 [LICENSE](LICENSE)。本展示包保留来源与许可；若后续分发程序，应同时提供对应版本完整源码、构建说明与许可。

OpenAI Codex、微信 iLink、Python、Tkinter、Pillow、cryptography、PyInstaller 属于各自项目或服务。本作品不是 OpenAI 或腾讯官方产品。
