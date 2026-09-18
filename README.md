# Bilunavis.github.io

一个用于学习和验证 Git 基础工作流的最小示例仓库。

## 项目简介

本项目从 `hello world` 示例起步，现已包含一份 `README.md` 和一个可直接打开的 Git 命令练习网站。仓库可用于练习文件跟踪、提交、分支、合并以及远程仓库协作，没有运行时依赖或构建步骤。

## 项目状态

- Git 仓库已初始化
- 主分支：`main`
- 远端仓库：`origin`
- 网站入口：`index.html`

## 快速开始

### 环境要求

- Git 2.28 或更高版本
- 任意现代浏览器

### 进入仓库

```powershell
cd C:\Users\Mark-\Desktop\github
```

### 打开网站

直接用浏览器打开 `index.html`，或在仓库目录中启动本地静态服务器：

```powershell
python -m http.server 8000
```

然后访问 `http://127.0.0.1:8000/`。

## 项目结构

```text
Bilunavis.github.io/
├── index.html  # Git 命令练习网站
├── README.md   # 项目说明
└── test/       # 预留的测试与练习目录
```

## 基本工作流

```bash
# 查看文件变化
git status

# 将指定文件加入暂存区
git add <file>

# 提交暂存区中的修改
git commit -m "描述本次修改"

# 查看提交历史
git log --oneline
```

## 后续扩展

- 在 `test/` 中补充更多 Git 操作示例
- 为网站增加更多练习内容
- 通过 `main` 分支持续更新远端仓库

## 许可证

当前尚未声明许可证。
