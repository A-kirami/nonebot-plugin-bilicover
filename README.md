<div align="center">
  <a href="https://v2.nonebot.dev/store"><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo"></a>
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>

<div align="center">

# nonebot-plugin-bilicover

_✨ B站视频封面提取 ✨_


<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/A-kirami/nonebot-plugin-bilicover.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-bilicover">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-bilicover.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

## 📖 介绍

提取B站视频的封面, 支持链接、av号、bv号

## 💿 安装

<details>
<summary>使用 nb-cli 安装</summary>
在 nonebot2 项目的根目录下打开命令行, 输入以下指令即可安装

    nb plugin install nonebot-plugin-bilicover

</details>

<details>
<summary>使用包管理器安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令

<details>
<summary>pip</summary>

    pip install nonebot-plugin-bilicover
</details>
<details>
<summary>pdm</summary>

    pdm add nonebot-plugin-bilicover
</details>
<details>
<summary>poetry</summary>

    poetry add nonebot-plugin-bilicover
</details>
<details>
<summary>conda</summary>

    conda install nonebot-plugin-bilicover
</details>

打开 nonebot2 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('nonebot_plugin_bilicover')

</details>

<details>
<summary>从 github 安装</summary>
在 nonebot2 项目的插件目录下, 打开命令行, 输入以下命令克隆此储存库

    git clone https://github.com/A-kirami/nonebot-plugin-bilicover.git

打开 nonebot2 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('src.plugins.nonebot_plugin_bilicover')

</details>

## 🎉 使用
### 指令表
| 指令 | 说明 |
|:-----:|:----:|
| 提取封面 + 视频链接/av号/bv号 | 提取对应视频的封面图片 |
