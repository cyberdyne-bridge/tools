# NOTICE

## 生成方式

本仓工具由作者主导设计并实测，**借助 AI 辅助编写**（DeepSeek V4 / Qwen 系列）。
所有性能数字来自作者本机实测（含踩坑记录），不是模型生成的估计值。

## 第三方

| 组件 | 用途 | 许可 / 说明 |
|---|---|---|
| `ffmpeg` / `ffprobe` | 解码、编码、音频链路 | LGPL/GPL，以发行版为准，本仓不分发二进制 |
| [`rife-ncnn-vulkan`](https://github.com/nihui/rife-ncnn-vulkan) | RIFE 插帧推理 | MIT，本仓不分发模型与可执行文件，由用户自行下载 |
| RIFE 模型（rife-v4.6 等） | 插帧权重 | 随 rife-ncnn-vulkan 发布，遵循其原许可 |

## 上游项目关系（仅"服务于"，非代码来源）

`interp/` 最初是为了给桌宠素材补帧而写的，README 里提到的上游项目是**被服务的对象**，不是本工具的代码来源：

| 项目 | 关系 |
|---|---|
| [PC2005-cloud/dsh-pet](https://github.com/PC2005-cloud/dsh-pet) | 上游根项目（MIT） |
| [MerZlin/dsh-pet-indesktop](https://github.com/MerZlin/dsh-pet-indesktop) | 上游移植版（MIT），本工具直接服务 |

> 早先版本仓里的 `LICENSE` 误抄了上游的版权行（Merzlin）。本仓已更正为作者本人，
> 上游项目的署名保留在本文与 `interp/` 的说明中。
