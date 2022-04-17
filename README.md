# Floppy and 3×USB 2.0 Hub

⭐ 模拟软盘与 3×USB 2.0 集线器 ⭐

[![pipeline status](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/badges/master/pipeline.svg)](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/-/commits/master)
[![Latest Release](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/-/badges/release.svg)](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/-/releases)
[![vercel](https://vercelbadge.soraharu.com/?app=interactivehtmlbom)](https://interactivehtmlbom.soraharu.com/)

🔗 [GitLab (Homepage)](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub) | 🔗 [OSHWHub](https://oshwhub.com/yanranxiaoxi/Floppy-and-3-USB-2-0-Hub) | 🔗 [GitHub](https://github.com/yanranxiaoxi/Floppy-and-3-USB-2.0-Hub)

![实拍图](https://downloadserver.soraharu.com:7000/Floppy%20and%203%C3%97USB%202.0%20Hub/Image/Product_quality_5.jpg)

## 🤔 这是什么

这是一个包含模拟软盘的 3×USB 2.0 集线器，使用 [立创 EDA](https://lceda.cn/) 进行开发。

模拟软盘部分采用 CH331A 芯片作为主控，24C256 作为存储芯片，可以提供~~高达~~ 32KiB 的存储空间。除此外，本作品还具有 3×USB 2.0 集线器，可以作为普通集线器使用。

*添加模拟软盘纯属为了六边形的规整又不想浪费那一个 USB 接口的折(~~yu~~)中(~~chun~~)方式，建议选择不焊接模拟软盘部分电路。

## 🍭 使用说明

本 PCB 设计已通过完整功能性测试，且已添加 [嘉立创](https://www.jlc.com/) SMT 定位孔，可直接进行 SMT 贴片生产。但请注意，本设计完整开源并遵循 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 开源协议，开源作者不对作品的安全性、完整性作任何承诺，且不对因此产生的任何损失承担后果。

你可以使用本项目的 [焊接助手](https://interactivehtmlbom.soraharu.com/Floppy-and-3-USB-2.0-Hub.html) 有效地提升手工焊接效率，本助手通过 [InteractiveHtmlBom](https://gitlab.soraharu.com/XiaoXi/InteractiveHtmlBom) 流水线自动化生成。

## 🛠️ 生产电路板

本项目的 Gerber 文件可以从 [Releases](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/-/releases) 页面获取，并允许在开源许可范围内的商业目的使用。

*建议使用 [嘉立创](https://www.jlc.com/) 生产高品质电路板。

*It is recommended to use [JLCPCB](https://jlcpcb.com/) to produce high-quality circuit boards.

## ⚙️ 部署至 EasyEDA

1. 克隆本项目 [源代码](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/-/archive/master/Floppy-and-3-USB-2.0-Hub-master.zip) 到本地
2. 在立创 EDA 标准版编辑器中选择 `文件` -> `打开` -> `立创EDA...`
3. 选择本项目源代码中的 `/EasyEDA/*.json` 文件并分别导入

## 🔤 字体

警告：本项目包含仅个人使用（禁止商用）和免费个人使用（付费商用）的字体素材，虽然本设计授权用户在开源许可范围内的商业目的使用，但是项目所使用的字体库并不包含在该授权范围内，商业使用时请注意处理版权风险。

- SAO UI Regular | [下载](https://www.deviantart.com/darkblackswords/art/Sword-Art-Online-Font-Download-426603647) | [官方](https://www.deviantart.com/darkblackswords/art/Sword-Art-Online-Font-342305125) | Only for Personal Use, Not for Commercial Use
- 字玩翻滚积木简 | [官方](http://www.reeji.com/font/1cb912a968b7721aaf83d9e405c6d48b) | Free for Personal Use

## 📜 开源许可

基于 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 许可进行开源。

本设计已在 [中国版权保护中心](https://www.ccopyright.com.cn/) 登记注册。
