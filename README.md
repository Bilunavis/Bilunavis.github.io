# GitHub

一个用于学习和验证 Git 基础工作流的最小示例仓库。

## 项目简介

本项目从 `hello world` 示例起步，仓库已经完成 Git 初始化，可用于练习文件跟踪、提交、分支、合并以及远程仓库协作。当前没有运行时依赖、构建步骤或可执行程序。

## 项目状态

- Git 仓库已初始化
- 默认分支：`master`
- 尚未创建首次提交

## 快速开始

### 环境要求

- Git 2.28 或更高版本

### 进入仓库

```powershell
cd C:\Users\Mark-\Desktop\github
```

### 查看仓库状态

```bash
git status
```

## 项目结构

```text
github/
├── README.md
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

- 在 `test/` 中补充 Git 操作示例
- 添加项目代码和自动化测试
- 配置远程仓库并推送首次提交

## 许可证

当前尚未声明许可证。
