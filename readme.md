<div align="center">

# ComfyUI Video Depth Anything
<a href="https://arxiv.org/abs/2501.12375"><img src='https://img.shields.io/badge/arXiv-Video Depth Anything-red' alt='Paper PDF'></a>
<a href='https://videodepthanything.github.io'><img src='https://img.shields.io/badge/Project_Page-Video Depth Anything-green' alt='Project Page'></a>

This project is an unofficial ComfyUI implementation of [Video Depth Anything](https://github.com/DepthAnything/Video-Depth-Anything),  for depth estimation on long videos without compromising quality, consistency, or generalization ability.

![0126-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/2db00d84-9de3-434b-a36b-1981f4399e09)

</div>

## ⭐ Support
If you like my projects and wish to see updates and new features, please consider supporting me. It helps a lot! 

[![ComfyUI-Depth-Anything-Tensorrt](https://img.shields.io/badge/ComfyUI--Depth--Anything--Tensorrt-blue?style=flat-square)](https://github.com/yuvraj108c/ComfyUI-Depth-Anything-Tensorrt)
[![ComfyUI-Upscaler-Tensorrt](https://img.shields.io/badge/ComfyUI--Upscaler--Tensorrt-blue?style=flat-square)](https://github.com/yuvraj108c/ComfyUI-Upscaler-Tensorrt)
[![ComfyUI-Dwpose-Tensorrt](https://img.shields.io/badge/ComfyUI--Dwpose--Tensorrt-blue?style=flat-square)](https://github.com/yuvraj108c/ComfyUI-Dwpose-Tensorrt)
[![ComfyUI-Rife-Tensorrt](https://img.shields.io/badge/ComfyUI--Rife--Tensorrt-blue?style=flat-square)](https://github.com/yuvraj108c/ComfyUI-Rife-Tensorrt)

[![ComfyUI-Whisper](https://img.shields.io/badge/ComfyUI--Whisper-gray?style=flat-square)](https://github.com/yuvraj108c/ComfyUI-Whisper)
[![ComfyUI_InvSR](https://img.shields.io/badge/ComfyUI__InvSR-gray?style=flat-square)](https://github.com/yuvraj108c/ComfyUI_InvSR)
[![ComfyUI-Thera](https://img.shields.io/badge/ComfyUI--Thera-gray?style=flat-square)](https://github.com/yuvraj108c/ComfyUI-Thera)
[![ComfyUI-Video-Depth-Anything](https://img.shields.io/badge/ComfyUI--Video--Depth--Anything-gray?style=flat-square)](https://github.com/yuvraj108c/ComfyUI-Video-Depth-Anything)
[![ComfyUI-PiperTTS](https://img.shields.io/badge/ComfyUI--PiperTTS-gray?style=flat-square)](https://github.com/yuvraj108c/ComfyUI-PiperTTS)

[![buy-me-coffees](https://i.imgur.com/3MDbAtw.png)](https://www.buymeacoffee.com/yuvraj108cZ)
[![paypal-donation](https://i.imgur.com/w5jjubk.png)](https://paypal.me/yuvraj108c)
---

## Installation

Navigate to the ComfyUI `/custom_nodes` directory

```bash
git clone https://github.com/yuvraj108c/ComfyUI-Video-Depth-Anything.git
cd ./ComfyUI-Video-Depth-Anything
pip install -r requirements.txt
```

Xformers (optional)
```bash
pip install xformers
```

## Usage
- Load [example workflow](workflows/video_depth_anything.json) 
- Models will download automatically to `ComfyUI/models/videodepthanything`

## Note
- The large model doesn't work with 24GB vram

## Changelog
**9 February 2025**
- Support autocast inference, minor cleanups


## Citation

```bibtex
@article{video_depth_anything,
  title={Video Depth Anything: Consistent Depth Estimation for Super-Long Videos},
  author={Chen, Sili and Guo, Hengkai and Zhu, Shengnan and Zhang, Feihu and Huang, Zilong and Feng, Jiashi and Kang, Bingyi}
  journal={arXiv:2501.12375},
  year={2025}
}
```
## LICENSE
- Video-Depth-Anything-Small model is under the Apache-2.0 license. 
- Video-Depth-Anything-Large model is under the CC-BY-NC-4.0 license.
