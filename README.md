# 🚀 AI-Driven Tech Blog

> 告诉 Claude 你想了解的技术主题，剩下的交给她

[![Vercel](https://img.shields.io/badge/Vercel-Ready-brightgreen?style=flat-square&logo=vercel)](https://vercel.com)
[![Hexo](https://img.shields.io/badge/Hexo-5.4.0-blue?style=flat-square&logo=hexo)](https://hexo.io)
[![Theme](https://img.shields.io/badge/Theme-Fluid-4B89AE?style=flat-square)](https://github.com/fluid-dev/hexo-theme-fluid)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)]()

---

## 💡 理念

> 我只需要告诉 Claude 我想要了解的技术主题，她就会自动帮我搜集资料，整理好文章，最后发布到博客上。

这是一个**AI 驱动的自动化博客**。借助 Claude 的能力，实现了一种全新的写作体验：

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  🎯 说出想法  │ -> │  🤖 AI 搜集  │ -> │  📝 自动写作  │ -> │  ✅ 人工确认  │
└─────────────┘     └─────────────┘     └─────────────┘     └─────────────┘
                                                                    │
                                                                    v
                                              ┌─────────────────────────────────┐
                                              │  🚀 自动推送到 GitHub -> Vercel  │
                                              └─────────────────────────────────┘
```

## ✨ 特性

- 🤖 **AI 全自动写作** - 从选题到成文，AI 一站式完成
- ⚡ **零门槛创作** - 只需描述你想了解的技术主题
- 🔍 **资料自动搜集** - 优先官方文档，确保严谨性
- 📊 **架构图辅助** - 用图表讲清楚技术原理
- 🚀 **自动部署** - Push 即发布，Vercel 无缝衔接

## 🛠️ 技术栈

```
┌─────────────────────────────────────────────────────────────┐
│                        AI Layer                             │
├─────────────────────────────────────────────────────────────┤
│              Claude 5  │  全自动资料搜集与整理                 │
├─────────────────────────────────────────────────────────────┤
│                     Hexo Framework                          │
├─────────────────────────────────────────────────────────────┤
│     Hexo 5.4.0     │     Fluid 1.9      │     Vercel       │
└─────────────────────────────────────────────────────────────┘
```

## 🎯 工作流

| 步骤 | 操作 | 说明 |
|:---:|------|------|
| 1️⃣ | **告诉 Claude 主题** | 我："帮我写一篇关于 Kubernetes 的文章" |
| 2️⃣ | **AI 自动完成** | Claude 搜集资料、整理文章、生成配图 |
| 3️⃣ | **本地预览确认** | `hexo server -p 80` 查看效果 |
| 4️⃣ | **自动发布** | 推送到 GitHub，自动部署到 Vercel |

## 📁 项目结构

```
blog_ai/
├── source/
│   └── _posts/          # 📄 博客文章 (AI 生成 + 人工审核)
├── themes/
│   └── fluid/           # 🎨 Fluid 主题
├── scripts/            # 🤖 AI 自动化脚本 (可选)
├── db.json              # 📦 文章数据库
├── _config.yml          # ⚙️ Hexo 配置
└── package.json         # 📦 依赖管理
```

## 🚀 快速开始

### 创建新文章

```bash
hexo new "文章标题"
```

### 本地预览

```bash
hexo server -p 80
```

### 部署上线

```bash
git push
# 自动部署到 Vercel
```

## 📝 文章风格

- 深度技术文章，注重实战经验
- 包含可运行的代码示例
- 优先官方文档，确保技术准确性
- 使用架构图辅助理解复杂概念
- 语言：中文

## 🔗 链接

- 📖 [博客预览](https://ai-blog-psi.vercel.app)
- 🐙 [GitHub 仓库](https://github.com/com-wushuang/ai_blog)

---

*让 AI 释放创造力，让技术分享更简单*
