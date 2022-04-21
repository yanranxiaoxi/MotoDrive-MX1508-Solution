# MotoDrive MX1508 Solution

⭐ 双路直流电机驱动 MX1508 方案 ⭐

[![pipeline status](https://gitlab.soraharu.com/XiaoXi/MotoDrive-MX1508-Solution/badges/master/pipeline.svg)](https://gitlab.soraharu.com/XiaoXi/MotoDrive-MX1508-Solution/-/commits/master) [![Latest Release](https://gitlab.soraharu.com/XiaoXi/MotoDrive-MX1508-Solution/-/badges/release.svg)](https://gitlab.soraharu.com/XiaoXi/MotoDrive-MX1508-Solution/-/releases) [![vercel](https://vercelbadge.soraharu.com/?app=interactivehtmlbom)](https://interactivehtmlbom.soraharu.com/)

🔗 [GitLab (Homepage)](https://gitlab.soraharu.com/XiaoXi/MotoDrive-MX1508-Solution) | 🔗 [OSHWHub](https://oshwhub.com/yanranxiaoxi/MotoDrive-MX1508-Solution) | 🔗 [GitHub](https://github.com/yanranxiaoxi/MotoDrive-MX1508-Solution)

![实拍图](https://downloadserver.soraharu.com:7000/MotoDrive%20MX1508%20Solution/Image/Product_quality_5.jpg)

## 🤔 这是什么

这是一个使用 MX1508 制作的玩具电机驱动，使用 [立创 EDA](https://lceda.cn/) 进行开发。

本设计采用 MX1508 作为驱动芯片，总体布局及使用方法和 L298N 方案一致。

建议使用小型板设计，CubeSmall 版型只是为了兼容 50mm 标准规格的一种妥协。

## 🍭 使用说明

本 PCB 设计已通过完整功能性测试，且已添加 [嘉立创](https://www.jlc.com/) SMT 定位孔，可直接进行 SMT 贴片生产。但请注意，本设计完整开源并遵循 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 开源协议，开源作者不对作品的安全性、完整性作任何承诺，且不对因此产生的任何损失承担后果。

你可以使用本项目的 [焊接助手](https://interactivehtmlbom.soraharu.com/MotoDrive-MX1508-Solution.html) 有效地提升手工焊接效率，本助手通过 [InteractiveHtmlBom](https://gitlab.soraharu.com/XiaoXi/InteractiveHtmlBom) 流水线自动化生成。

## 🏃 主要性能参数

- 电机驱动通道：双通道
- 最大输入电压：9.6V
- 单通道持续输出电流：1.35A
- 单通道最大峰值输出电流：2A
- 双通道持续输出电流：1A

## 🛠️ 生产电路板

本项目的 Gerber 文件可以从 [Releases](https://gitlab.soraharu.com/XiaoXi/MotoDrive-MX1508-Solution/-/releases) 页面获取，并允许在开源许可范围内的商业目的使用。

*建议使用 [嘉立创](https://www.jlc.com/) 生产高品质电路板。

*It is recommended to use [JLCPCB](https://jlcpcb.com/) to produce high-quality circuit boards.

## ⚙️ 部署至 EasyEDA

1. 克隆本项目 [源代码](https://gitlab.soraharu.com/XiaoXi/MotoDrive-MX1508-Solution/-/archive/master/MotoDrive-MX1508-Solution-master.zip) 到本地
2. 在立创 EDA 标准版编辑器中选择 `文件` -> `打开` -> `立创EDA...`
3. 选择本项目源代码中的 `/EasyEDA/*.json` 文件并分别导入

## 📜 开源许可

基于 [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) 许可进行开源。

本设计已在 [中国版权保护中心](https://www.ccopyright.com.cn/) 登记注册。
