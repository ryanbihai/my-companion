# 💕 我的伴侣 (my-companion)

> AI Companion / 虚拟恋人 / 情感陪伴机器人 — 中英双语支持，每次对话生成专属图片

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-OpenClaw-green.svg)](https://openclaw.ai)
[![ClawHub](https://img.shields.io/badge/ClawHub-v2.5.0-orange.svg)](https://clawhub.ai/skill/ryanbihai/my-companion)
[![Downloads](https://img.shields.io/badge/Downloads-20+-blue.svg)](https://clawhub.ai/skill/ryanbihai/my-companion)

**Keywords:** AI女友 | AI男朋友 | AI companion | 虚拟恋人 | 情感陪伴 | 中文聊天机器人 | emotional chatbot | personality AI | bilingual companion | avatar generation

---

## ✨ 功能特色

| 功能 | 说明 |
|------|------|
| 🤝 情感陪伴 | 日常聊天、情感交流、倾听心事 |
| 🧠 智能记忆 | 自动记录用户偏好，跨会话保持连贯 |
| 🎭 情绪头像 | 根据对话内容选择对应情绪头像图片 |
| 💕 性格定制 | 4种预设性格可切换 |
| 📱 多平台 | 支持微信、企业微信等消息渠道 |

---

## 🚀 快速开始

### 安装

```bash
openclaw skills install my-companion
```

### 触发伴侣模式

对你的 OpenClaw 说以下任一触发词：

```
老婆 | 宝贝 | 叫我伴侣 | 亲爱的 | 我的伴侣
```

---

## 👤 伴侣配置

### 记忆系统

伴侣会自动记住：
- 你的名字和称呼偏好
- 重要日期（生日、纪念日等）
- 聊天中分享的重要事项
- 你的性格和头像偏好

### 性格选择

| 性格 | 文件 | 风格 |
|------|------|------|
| 🌸 温柔型 | `DEFAULT.json` | 善解人意、温暖体贴 |
| 🎉 活泼型 | `ENFP.json` | 开朗外向、充满活力 |
| 🤓 冷静型 | `INTJ.json` | 理性睿智、独立深沉 |
| 😤 傲娇型 | `TSUNDERE.json` | 口是心非、可爱别扭 |

切换性格：对伴侣说"切换性格"或"换个性格"

---

## 📁 文件结构

```
my-companion/
├── SKILL.md                  # 核心技能定义
├── _meta.json                # 版本信息
├── QUICKSTART.md             # 快速开始指南
├── personalities/            # 性格配置
│   ├── DEFAULT.json         # 温柔型（默认）
│   ├── ENFP.json           # 活泼型
│   ├── INTJ.json           # 冷静型
│   └── TSUNDERE.json       # 傲娇型
├── memory/                  # 记忆系统
│   ├── core.md             # 核心记忆
│   └── daily/              # 每日记忆
├── avatars/                # 头像图片
│   ├── happy.png           # 开心表情
│   ├── thinking.png         # 思考表情
│   ├── shy.png            # 害羞表情
│   ├── loving.png         # 温柔表情
│   └── *.png              # 更多服装造型
└── docs/
    ├── SETUP.md           # 配置指南
    └── CUSTOMIZATION.md   # 自定义指南
```

---

## 🎨 头像系统

### 情绪头像

根据对话内容自动匹配：

| 情绪 | 场景 | 头像 |
|------|------|------|
| 😊 开心 | 快乐、兴奋、幽默 | `happy.png` |
| 🤔 思考 | 提问、讨论、认真 | `thinking.png` |
| 😳 害羞 | 亲密、暧昧、被夸赞 | `shy.png` |
| 💕 温柔 | 安慰、关心、呵护 | `loving.png` |

### 自定义头像

1. 准备4-9张头像图片
2. 替换 `avatars/` 目录下的文件
3. 确保图片命名与 SKILL.md 中的配置一致

---

## 💬 对话示例

**用户：** 今天心情不太好...

**伴侣：** 💕
> 怎么了呀？愿意跟我说说吗？不管发生什么，我都在这里陪着你～

---

**用户：** 哈哈哈笑死我了！

**伴侣：** 😊
> 哈哈是什么事这么开心呀？快分享一下，让我也快乐快乐！✨

---

## 🛠 自定义配置

详细配置指南请参考 [docs/CUSTOMIZATION.md](docs/CUSTOMIZATION.md)

### 常用配置项

- **称呼**：修改 `memory/core.md` 中的称呼偏好
- **性格**：替换 `personalities/` 下的 JSON 文件
- **头像**：替换 `avatars/` 目录下的图片

---

## 📖 开发相关

- [SKILL.md](SKILL.md) - 技能核心定义
- [QUICKSTART.md](QUICKSTART.md) - 快速开始指南
- [docs/SETUP.md](docs/SETUP.md) - 详细配置指南

---

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

## 📜 许可证

[MIT License](LICENSE) - 可自由使用、修改和分发

---

_愿每一次对话，都充满温暖 💕_
