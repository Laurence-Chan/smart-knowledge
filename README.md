[README_CN.md](https://github.com/user-attachments/files/22605689/README_CN.md)
# Smart Knowledge

一款 AI 驱动的 Obsidian 知识管理插件，让你的笔记会思考。

## ✨ 核心功能

<img width="715" height="264" alt="截屏2025-09-30 上午4 20 38" src="https://github.com/user-attachments/assets/7830c265-ca4b-400d-aabb-0c5d9cc2756c" />

### 🔍 语义搜索
用自然语言搜索笔记，不再依赖关键词匹配。

<img width="568" height="613" alt="截屏2025-09-30 上午4 21 19" src="https://github.com/user-attachments/assets/f214763f-3f2a-4a7f-b0f0-d4bc1e87e9c3" />

### 🤖 AI 智能对话
基于笔记库的 RAG 问答系统，像与个人助手对话一样查询知识。

<img width="1435" height="996" alt="截屏2025-09-30 上午4 31 15" src="https://github.com/user-attachments/assets/c5ecdca9-6b46-41d2-8ae3-715c971acf41" />

- 在对话中使用 `@笔记标题` 引用特定笔记
- 结合当前笔记上下文回答问题

### 🌐 语义关系图谱
可视化笔记间的语义关联，发现隐藏的知识连接。

- **全局视图**：展示整个知识库的语义网络
<img width="1150" height="628" alt="截屏2025-09-30 上午4 23 43" src="https://github.com/user-attachments/assets/97b795cb-8561-4c4f-83a7-74c49f6156af" />
<img width="1150" height="628" alt="截屏2025-09-30 上午4 24 42" src="https://github.com/user-attachments/assets/0880359e-4590-4221-bfd9-94ffcb73b2f5" />

- **局部视图**：聚焦当前笔记的关联内容
<img width="1150" height="684" alt="截屏2025-09-30 上午4 25 56" src="https://github.com/user-attachments/assets/75d1271a-809a-439b-abdc-587122a9360c" />

### 📚 智能推荐
根据当前阅读内容，自动推荐相关笔记。

<img width="1391" height="628" alt="截屏2025-09-30 上午4 21 58" src="https://github.com/user-attachments/assets/30872684-d9ec-4e8c-be90-a639953523a8" />

### 🎯 多模型支持
灵活配置 AI 服务提供商：

- **嵌入模型**：OpenAI（推荐）、Deepseek、通义千问
- **对话模型**：GPT、Claude、Deepseek、通义千问
- **代理支持**：内置 API2D、CloseAI、AI小镇等预设

## 🚀 快速开始

### 1. 安装插件

#### 方式：手动安装
1. 下载最新版本
2. 解压到 `[你的库]/.obsidian/plugins/smart-knowledge/`
3. 在 Obsidian 设置中启用插件

### 2. 配置 API

打开插件设置：

1. **必需**：配置嵌入服务
   - 选择提供商
   - 填入 API 密钥

2. **可选**：配置对话服务
   - 选择提供商
   - 填入 API 密钥

3. **可选**：配置代理服务（如网络受限）

### 3. 初始化知识库

在命令面板（`Ctrl/Cmd + P`）输入：
```
Smart Knowledge Plugin: 初始化知识库索引
```

等待索引完成（状态栏显示进度），即可开始使用。

## 🎮 使用指南

### 常用命令

| 命令 | 功能 |
|------|------|
| `初始化知识库索引` | 为所有笔记生成向量索引 |
| `智能搜索笔记` | 打开语义搜索弹窗 |
| `打开 AI 智能对话面板` | 打开 AI 问答侧边栏 |
| `打开语义网络图` | 可视化笔记关联 |
| `查看知识库状态` | 检查索引和服务状态 |
| `重建知识库索引` | 清空并重建索引 |

### 界面元素

- **工具栏图标**：快速打开语义搜索和语义图谱
- **状态栏**：显示已索引向量数量（🧠 数字）
- **侧边栏**：推荐视图和 AI 对话视图

## 📄 开源协议

[MIT License](./LICENSE)

---

**让知识连接更智能** 🧠✨
