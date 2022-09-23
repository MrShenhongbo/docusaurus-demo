---
sidebar_position: 1
---

# 教程介绍

让我们在 **不到 5 分钟的时间内** 了解 Docusaurus。

## 入门

通过 **创建一个新站点** 开始。

Or **try Docusaurus immediately** with **[docusaurus.new](https://docusaurus.new)**.
或者使用 **[docusaurus.new](https://docusaurus.new)** 立即尝试 **Docusaurus**

### 你需要什么

- [Node.js](https://nodejs.org/en/download/) 16.14 或更高版本：
  - 安装 Node.js 时，建议勾选所有依赖相关的复选框。

## 生成新站点

使用 **classic 模板** 生成新的 Docusaurus 站点。

运行命令后，**classic 模板** 将自动添加到您的项目中：

```bash
npm init docusaurus@latest my-website classic
```

您可以将此命令键入 Command Prompt、Powershell、Terminal 或代码编辑器的任何其他集成终端。

该命令还会安装运行 Docusaurus 所需的所有必要依赖项。

## 启动您的网站

运行开发服务器：

```bash
cd my-website
npm run start
```

该 `cd` 命令更改您正在使用的目录。为了使用您新创建的 Docusaurus 站点，您需要在那里导航终端。

该 `npm run start` 命令在本地构建您的网站并通过开发服务器提供服务，您可以在 http://localhost:3000/ 上查看。

打开 `docs/intro.md`（此页面）并编辑一些行：站点会 **自动重新加载** 并显示您的更改。
