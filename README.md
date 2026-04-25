<p align="left">
    <span>
        <b>中文</b>
    </span>
    <span> • </span>
    <a href="README_en.md">
        English
    </a>
    <span> • </span>
    <a href="README_ja.md">
        日本語
    </a>
</p>

<p align="center">
  <a href="https://github.com/hiroi-sora/Umi-OCR">
    <img width="200" height="128" src="https://tupian.li/images/2022/10/27/icon---256.png" alt="Umi-OCR">
  </a>
</p>

<h1 align="center">Umi-OCR 文字识别工具</h1>

<p align="center">
  <a href="https://github.com/hiroi-sora/Umi-OCR/releases/latest">
    <img src="https://img.shields.io/github/v/release/hiroi-sora/Umi-OCR?style=flat-square" alt="Umi-OCR">
  </a>
  <a href="https://github.com/hiroi-sora/Umi-OCR/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/hiroi-sora/Umi-OCR?style=flat-square" alt="LICENSE">
  </a>
  <a href="#下载发行版">
    <img src="https://img.shields.io/github/downloads/hiroi-sora/Umi-OCR/total?style=flat-square" alt="forks">
  </a>
  <a href="https://star-history.com/#hiroi-sora/Umi-OCR">
    <img src="https://img.shields.io/github/stars/hiroi-sora/Umi-OCR?style=flat-square" alt="stars">
  </a>
  <a href="https://github.com/hiroi-sora/Umi-OCR/forks">
    <img src="https://img.shields.io/github/forks/hiroi-sora/Umi-OCR?style=flat-square" alt="forks">
  </a>
  <a href="https://hosted.weblate.org/engage/umi-ocr/">
    <img src="https://hosted.weblate.org/widget/umi-ocr/svg-badge.svg" alt="翻译状态">
  </a>
</p>

<div align="center">
  <h3>
    <a href="#目录">
      使用说明
    </a>
    <span> • </span>
    <a href="#下载发行版">
      下载地址
    </a>
    <span> • </span>
    <a href="CHANGE_LOG.md">
      更新日志
    </a>
    <span> • </span>
    <a href="https://github.com/hiroi-sora/Umi-OCR/issues">
      提交Bug
    </a>
  </h3>
</div>
<br>

<div align="center">
  <strong>免费，开源，可批量的离线OCR软件</strong><br>
  <sub>适用于 Windows7 x64 、Linux x64
</div><br>

> **个人备注**：此 fork 主要用于学习和研究 OCR 工作流，以及测试 HTTP 接口的集成用法。上游仓库：[hiroi-sora/Umi-OCR](https://github.com/hiroi-sora/Umi-OCR)

- **免费**：本项目所有代码开源，完全免费。
- **方便**：解压即用，离线运行，无需网络。
- **高效**：自带高效率的离线OCR引擎，内置多种语言识别库。
- **灵活**：支持命令行、HTTP接口等外部调用方式。
- **功能**：截图OCR / 批量OCR / PDF识别 / 二维码 / 公式识别

<p align="center"><img src="https://tupian.li/images/2023/11/19/65599097ab5f4.png" alt="1-标题-1.png" style="width: 80%;"></p>

![1-标题-2.png](https://tupian.li/images/2023/11/19/6559909fdeeba.png)

## 目录

- [截图识别](#截图OCR)
  - [排版解析](#文本后处理) - 识别不同排版，按正确顺序输出文字
- [批量识别](#批量OCR)
  - [忽略区域](#忽略区域) - 排除截图水印处的文字
- [二维码](#二维码) 支持扫码或生成二维码图片
- [文档识别](#文档识别) 从PDF扫描件中提取文本，或转为双层可搜索PDF
- [全局设置](#全局设置)
- [命令行调用](docs/README_CLI.md)
- [HTTP接口](docs/http/README.md)
- [构建项目（Windows、Linux）](#构建项目)

## 使用源码

开发者请务必阅读 [构建项目](#构建项目) 。

## 下载发行版

以下发布链接均长期维护，提供稳定版本的下载。

- **蓝奏云** https://hiroi-sora.lanzoul.com/s/umi-ocr （国内推荐，免注册/无限速）
- **GitHub** https://github.com/hiroi-sora/Umi-OCR/releases/latest
- **Source Forge** https://sourceforge.net/projects/umi-ocr


<details>
<summary><b>•&nbsp;&nbsp;Scoop Installer</b>（点击展开）</summary>

[Scoop](https://scoop.sh/) 是一款Windows下的命令行安装程序，可方便地管理多个应用。您可以先安装 Scoop ，再使用以下指令安装 `Umi-OCR` ：

- 添加 `extras` 桶：
```
scoop bucket add extras
```

- （可选
```