# vLLM-China - 本地LLM推理引擎（中文优化版）

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![vLLM](https://img.shields.io/badge/vLLM-v0.16.0-blue.svg)](https://github.com/vllm-project/vllm)

## 📖 简介

**vLLM-China** 是vLLM的中文优化版本，专注于为中国用户提供更好的使用体验：

- 🌏 **中文化界面** - CLI工具完全中文
- 🇨🇳 **国内模型支持** - 预配置通义千问、智谱AI、百川等
- 🚀 **简化部署** - 一键安装脚本
- 📡 **中国网络优化** - 国内镜像源支持

---

## ✨ 特性

### 核心功能（基于vLLM）
- ✅ 高吞吐量LLM推理
- ✅ PagedAttention内存管理
- ✅ 连续批处理
- ✅ OpenAI兼容API
- ✅ 多硬件支持（NVIDIA/AMD/Intel）

### 本地化改造
- 🌏 **中文CLI工具** - 完整中文界面
- 📚 **中文文档** - 详细使用说明
- 🇨🇳 **国内模型列表** - 默认配置国内大模型
- 🛠️ **一键安装** - 自动检测环境和依赖

---

## 📦 快速开始

### 安装

```bash
# 方式1：一键安装
curl -sSfL https://raw.githubusercontent.com/aafullso/vllm-china/main/install.sh | bash

# 方式2：手动安装
python3 -m venv venv
source venv/bin/activate
pip install vllm
```

### 使用

```bash
# 查看中文模型列表
vllm-china list-models

# 启动交互式菜单
vllm-china menu

# 直接启动模型
vllm-china serve --model qwen-7b-chat --device cuda
```

---

## 🌟 支持的国内模型

| 模型 | 描述 | 说明 |
|------|------|------|
| qwen-7b-chat | 通义千问 7B | 推荐入门 |
| qwen-14b-chat | 通义千问 14B | 中等配置 |
| baichuan-7b-chat | 百川 7B | 百川系列 |
| chatglm3-6b | 智谱 ChatGLM3 6B | 智谱AI |
| glm-4-9b-chat | 智谱 GLM-4 9B | 最新版本 |
| yi-6b-chat | 零一万物 Yi 6B | Yi系列 |
| internlm-7b-chat | 上海AI实验室 InternLM 7B | 国产模型 |

---

## 📚 文档

- 📖 [快速开始](QUICKSTART.md)
- 📝 [中文模型列表](docs/china-models.md)

---

## 📧 联系方式

- GitHub: [aafullso](https://github.com/aafullso)
- Email: 133301159@qq.com

---

**GitHub Stars订阅**：
[![Star History Chart](https://api.star-history.com/svg?repos=aafullso/vllm-china&type=Date)](https://star-history.com/#aafullso/vllm-china&Date)

---

**vLLM核心来自**：[vLLM Project](https://github.com/vllm-project/vllm)
