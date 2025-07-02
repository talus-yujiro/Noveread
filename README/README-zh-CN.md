# Noveread

## 语言

[英文](/README.md)  
[日文](/README/README-ja.md)
[中文](/README/README-zh-CN.md)

## 概要

您可以从网络小说服务下载小说，并使用阅读器进行阅读。  
也可以直接在网页上阅读。  

将其加入书签后，您可以随时访问。  

那么，祝您享受愉快的网络小说生活！👋

## 使用方法

请从 [Release](https://github.com/talus-yujiro/Noveread/releases) 页面下载最新版的可执行文件。

| 操作系统 | 发行版                 | 文件名                |
|----------|------------------------|-----------------------|
| Linux    | Debian, Ubuntu         | Noveread-*.deb        |
| Linux    | 其他发行版             | Noveread-*.AppImage   |
| Windows  | Windows 11 及以下       | Noveread.setup.*.exe  |

或者，下载源代码并在解压后的根目录中执行以下命令：

```bash
npm run dist
```

（需要预先安装 Node.js）

生成的可执行文件应会出现在 dist 文件夹中。

## 开发计划
- [x] v0.0.1 成功启动基本功能
- [ ] v0.5.0 实现下载处理功能
- [ ] v1.0.0 实现作为完整应用程序的使用体验

## 最近更新

### 2025/07/01

- 修改 `package.json`  
  - 添加支持构建 `.deb` 安装包以用于发布

### 2025/06/27

- 发布 v1.0.0  
  - 成功启动基本功能  
  - 试验性地引入 WebView