---
name: KeithleyControl
tools: [C#, KEITHLEY, WPF, MVVM, POWERSUPPLY]
image: https://raw.githubusercontent.com/linkmeta/linkmeta.github.io/main/assets/demo.png
description: KeithleyControl Support Keithley Powersupply control by LAN Interface. 基于WPF框架，MVVM模型开发，Keithley 电源控制，支持LAN口远程控制。
---

# KeithleyControl
![Test result](https://img.shields.io/badge/Windows-passing-green)
![GitHub License](https://img.shields.io/github/license/linkmeta/KeithleyControl?color=blue&style=flat-square)
![Issues](https://img.shields.io/github/issues/linkmeta/KeithleyControl?color=blue&style=flat-square)
![release](https://img.shields.io/github/release/linkmeta/KeithleyControl.svg)

![logo](https://raw.githubusercontent.com/linkmeta/linkmeta.github.io/d54202e24c6f92698cfa90eed6b27605dc034f80/assets/favicon.ico)

KeithleyControl Support Keithley Powersupply control by LAN Interface.
基于WPF框架，MVVM模型开发，Keithley 电源控制，支持LAN口远程控制。


## 功能列表

- [x] 电源控制基本功能（电压、电流、实时电流曲线）
- [x] 支持LAN口远程控制
- [x] 支持设置电压，电流
- [x] 支持实时获取电压电流值
- [x] 采用oxyplot实时绘制电流曲线
- [ ] GPIB控制（待开发）
<img src="https://raw.githubusercontent.com/linkmeta/linkmeta.github.io/main/assets/KeithleyControlDemo.gif" width="700">
<img src="https://raw.githubusercontent.com/linkmeta/linkmeta.github.io/main/assets/demo.png" width="700">
## 构建

- [x] VisualStudio 2022（基于 .NET WPF框架验证）

## 贡献
绘图采用了开源oxyplot,特此感谢


## License

软件采用 MIT License 授权（[License MIT](./LICENSE)）。

<p class="text-center">
{% include elements/button.html link="https://github.com/linkmeta/KeithleyControl" text="Learn More" %}
</p>