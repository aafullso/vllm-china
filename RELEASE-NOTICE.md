# vLLM-China v1.0.0 Release

🎉 **首次发布！vLLM-China中文优化版上线**

---

## ✨ 主要功能

### 核心功能（基于vLLM v0.16.0）
- ✅ 高吞吐量LLM推理引擎
- ✅ PagedAttention内存管理
- ✅ 连续批处理优化
- ✅ OpenAI兼容API接口
- ✅ 多硬件支持（NVIDIA/AMD/Intel CPU/GPU）

### 本地化改造
- 🌏 **中文CLI工具** - 完整的中文界面和提示
- 📚 **中文文档** - 详细的使用说明
- 🇨🇳 **国内模型支持** - 预配置10+国内大模型
- 🛠️ **简化部署** - 一键安装脚本
- 🌍 **中国网络优化** - 国内镜像源支持

---

## 📦 支持的国内模型

| 模型名称 | 描述 | 推荐硬件 |
|---------|------|---------|
| qwen-7b-chat | 通义千问 7B | 16GB GPU 或 32GB CPU |
| qwen-14b-chat | 通义千问 14B | 24GB GPU 或 64GB CPU |
| qwen-72b-chat | 通义千问 72B | 80GB GPU 或更高 |
| baichuan-7b-chat | 百川 7B | 16GB GPU 或 32GB CPU |
| baichuan-13b-chat | 百川 13B | 24GB GPU 或 64GB CPU |
| chatglm3-6b | 智谱 ChatGLM3 6B | 16GB GPU 或 32GB CPU |
| glm-4-9b-chat | 智谱 GLM-4 9B | 24GB GPU 或 64GB CPU |
| yi-6b-chat | 零一万物 Yi 6B | 16GB GPU 或 32GB CPU |
| yi-34b-chat | 零一万物 Yi 34B | 48GB GPU 或更高 |
| internlm-7b-chat | 上海AI实验室 InternLM 7B | 16GB GPU 或 32GB CPU |
| internlm2-20b-chat | 上海AI实验室 InternLM2 20B | 24GB GPU 或 64GB CPU |

---

## 🚀 快速开始

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

## 💡 核心优势

### 对比国外vLLM

| 特性 | vLLM（国外） | vLLM-China |
|------|-------------|------------|
| 界面语言 | 英文 | 🇨🇳 中文 |
| 默认模型 | 国外模型（Llama等） | 🇨🇳 国内模型（通义千问等） |
| 文档语言 | 英文 | 🇨🇳 中文 |
| 部署难度 | 中等 | ⭐ 简化（一键安装） |
| 中国网络优化 | 无 | ✅ 国内镜像源 |
| 适用人群 | 海外用户 | 🇨🇳 国内开发者 |

### 国内用户价值

1. **降低学习成本** - 完整中文界面和文档
2. **开箱即用** - 默认配置国内大模型
3. **访问加速** - 国内镜像源，减少等待
4. **技术支持** - 更容易理解和使用

---

## 📊 技术栈

- **核心引擎**：vLLM v0.16.0
- **编程语言**：Python 3.8+
- **CLI框架**：标准Python + argparse
- **依赖管理**：pip + 国内镜像源
- **部署方式**：pip安装 + Docker支持

---

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

### 改造计划

- [ ] 添加更多国内模型
- [ ] 支持更多文件格式
- [ ] Web界面
- [ ] 性能优化
- [ ] Docker镜像

---

## 📧 联系方式

- GitHub: [aafullso](https://github.com/aafullso)
- Email: 133301159@qq.com

---

## ⭐ Star History

如果觉得有用，请给个 Star ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=aafullso/vllm-china&type=Date)](https://star-history.com/#aafullso/vllm-china&Date)

---

**特别感谢**：
- [vLLM Project](https://github.com/vllm-project/vllm) - 核心推理引擎
- [清华大学KEG实验室](https://github.com/TsinghuaKEG) - Qwen模型
- [智谱AI](https://github.com/THUDM) - ChatGLM系列
- [零一万物](https://github.com/01-ai) - Yi系列
- [上海AI实验室](https://github.com/InternLM) - InternLM系列

---

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

vLLM 核心代码来自 [vLLM Project](https://github.com/vllm-project/vllm)，请遵守其许可证。

---

**vLLM-China - 让国内开发者更轻松地使用LLM！** 🇨🇳

---

**发布时间**：2026-03-02
**版本**：v1.0.0
**作者**：aafullso
