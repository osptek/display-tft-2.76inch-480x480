<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 2.76″ TFT 显示屏 480×480（YDP276BT004-V1）</h1>

<p align="center"><b>TFT 模组 · MIPI · ST7701S</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: MIPI" src="https://img.shields.io/badge/Interface-MIPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7701S" src="https://img.shields.io/badge/Driver-ST7701S-E7352C?style=flat-square" />
</p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 2.76 英寸 |
| 类型 | TFT |
| 分辨率 | 480×480 |
| 外形尺寸 | 73.03 x 76.48 mm |
| 有效显示区域 | Φ70.13 mm |
| 接口 | MIPI |
| 驱动 IC | ST7701S |
| 触摸驱动 | — |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`ST7701S_SPEC_ V1.3.pdf`](./datasheets/ST7701S_SPEC_%20V1.3.pdf) |
| 规格文档 | [`YDP276B004-V1.pdf`](./datasheets/YDP276B004-V1.pdf) |
| CAD 图纸 | [`YDP276B004-V1.dwg`](./cad/YDP276B004-V1.dwg) |
| CAD 图纸 | [`YDP276BT004-V1(在TFT276BT010基础上改盖板改屏FPC).dwg`](./cad/YDP276BT004-V1%28%E5%9C%A8TFT276BT010%E5%9F%BA%E7%A1%80%E4%B8%8A%E6%94%B9%E7%9B%96%E6%9D%BF%E6%94%B9%E5%B1%8FFPC%29.dwg) |
| CAD 图纸 | [`YDP276BT004-V1.dwg`](./cad/YDP276BT004-V1.dwg) |

## 仓库结构

```text
display-tft-2.76inch-480x480/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── YDP276BT004-V1/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        └── cad/              # 外形/盖板 CAD
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
