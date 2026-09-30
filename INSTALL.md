# 抖音自动化工作台安装说明

当前发布版本：1.1.3。下载文件：`dyAutoSuite-Setup-1.1.3.exe`（安装器原始文件名为“抖音自动化工作台 Setup 1.1.3.exe”，文件内容相同）。

1. 在 [Releases](../../releases) 中下载对应版本的 EXE 和 `SHA256SUMS.txt`。
2. 在 Windows PowerShell 中运行 `Get-FileHash -Algorithm SHA256 -LiteralPath '下载文件的完整路径'`，与校验文件中的值比较。
3. 双击 EXE，按安装向导完成安装，再从开始菜单启动。

该安装包没有 Windows 发布者代码签名，系统可能提示“未知发布者”。请确认下载地址位于 `github.com/vlaipro/dyAutoSuite-releases`，且文件校验值一致后再安装。

此版本的客户环境、账号授权和实际自动化流程仍需按交付场景验证。遇到安装或启动问题，请提供产品版本、Windows 版本和错误提示给威莱智能支持人员。
