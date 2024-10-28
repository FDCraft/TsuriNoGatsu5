

<div align="center">
<a href="version">
    <img src="./icon.png" alt="icon" style="zoom:200%;">
</a>

# Tsuri No Gatsu5

<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/FDCraft/TsuriNoGatsu5.svg" alt="license">
</a>

<a href="version">
    <img src="https://img.shields.io/badge/version-5.1.6-8A2BE2" alt="version">
</a>

</div>

## 这是什么？

>  作为 Tsuri No Gatsu 4 的贡献者之一，复旦大学基岩社有使用 Tsuri No Gatsu5 作为长期服的打算。但由于月见清兰淡出互联网，Tsuri No Gatsu 5 处于长期停止更新状态；此外 Tsuri No Gatsu 5 也并不完全符合本社团的现实情况。

Tsuri No Gatsu5 是一个注重田园体验的综合整合包，此外也将作为 FDCraft 自动化机械动力范畴教学整合包。

## 如何使用

为了防止服务端与客户端不匹配，Repo 采用类似 mrpack 的结构格式。

- `common` 为双端文件
- `client` 为客户端专有文件
- `server` 为服务端专用文件

要获得客户端，将`common` 文件夹中文件复制至 `client/overrides` 中，并更新 `mcbbs.packmeta` 中文件 hash 值。hash 值可以通过重新打包获取或者编写程序自动修改。

要获得服务端，将`common` 文件夹中文件复制至 `server` 中。不提供运行必须的原版服务端，请自行安装。
