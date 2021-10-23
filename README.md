# Floppy and 3×USB 2.0 Hub

⭐ 模拟软盘与 3×USB 2.0 集线器 ⭐

🔗 [GitLab (Homepage)](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub) | 🔗 [OSHWHub](https://oshwhub.com/yanranxiaoxi/Floppy-and-3-USB-2-0-Hub)

![实拍图](https://downloadserver.soraharu.com:7000/Floppy%20and%203%C3%97USB%202.0%20Hub/Image/Product_quality_5.jpg)

## 🤔 这是什么

这是一个包含模拟软盘的 3×USB 2.0 集线器，使用 [立创 EDA](https://lceda.cn/) 进行开发。

模拟软盘部分采用 CH331A 芯片作为主控，24C256 作为存储芯片，可以提供~~高达~~ 32KiB 的存储空间。除此外，本作品还具有 3×USB 2.0 集线器，可以作为普通集线器使用。

*添加模拟软盘纯属为了六边形的规整又不想浪费那一个 USB 接口的折(~~yu~~)中(~~chun~~)方式，建议选择不焊接模拟软盘部分电路。

你可以使用本项目的 [焊接助手](https://htmlpreview.soraharu.com/?https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/-/raw/master/InteractiveHtmlBom/index.html) 有效地提升手工焊接效率，本助手通过 [InteractiveHtmlBom](https://gitlab.soraharu.com/XiaoXi/InteractiveHtmlBom) 自动生成。

## 🛠️ 生产电路板

本项目的 Gerber 文件可以从 [Releases](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/-/releases) 页面获取，并允许在开源许可范围内的商业目的使用。

*建议使用 [嘉立创](https://www.jlc.com/) 生产高品质电路板。

*It is recommended to use [JLCPCB](https://jlcpcb.com/) to produce high-quality circuit boards.

## ⚙️ 部署至 EasyEDA

1. 克隆本项目 [源代码](https://gitlab.soraharu.com/XiaoXi/Floppy-and-3-USB-2.0-Hub/-/archive/master/Floppy-and-3-USB-2.0-Hub-master.zip) 到本地
2. 在立创 EDA 标准版编辑器中选择 `文件` -> `打开` -> `立创EDA...`
3. 选择本项目源代码中的 `/EasyEDA/1-*.json` 文件并分别导入

## 📜 开源许可

基于 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 许可进行开源。

本设计已在 [中国版权保护中心](https://www.ccopyright.com.cn/) 登记注册。
