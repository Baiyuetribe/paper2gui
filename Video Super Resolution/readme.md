# 视频超分

【快捷入口：[综述](readme.md) # [RealESRGAN-RAM](RealESRGAN-GUI-RAM.md) # [RealCugan](RealCugan-GUI.md) # [RealESRGAN](RealESRGAN-GUI.md) # [Waifu2x](waifu2x-gui.md) # [ReslSR](RealSR-GUI.md)】

## 开发者评价
> 截至2022年4月，视频超分辨百花齐放，不过目前主要在动漫领域表现出色，其中RealESGAN、RealCugan等算法已经明显优于waifu2x。
## 简介

超分辨技术源于图像智能放大技术，目前集成的所有工具都支持单张图片或单个视频进行超分辨放大，比如720p转4K.

## 效果演示：

![](../docs/images/styletransfer/iu.jpg)
![](https://github.com/bilibili/ailab/blob/main/Real-CUGAN/demos/title-compare1.png)
![](https://github.com/xinntao/Real-ESRGAN/raw/master/assets/teaser.jpg)
![](https://raw.githubusercontent.com/xinntao/public-figures/master/Real-ESRGAN/cmp_realesrgan_anime_1.png)
![](https://github.com/jixiaozhong/RealSR/blob/master/figures/0935.png)
<https://user-images.githubusercontent.com/17445847/145706977-98bc64a4-af27-481c-8abe-c475e15db7ff.MP4>

<https://user-images.githubusercontent.com/17445847/145707055-6a4b79cb-3d9d-477f-8610-c6be43797133.MP4>

<https://user-images.githubusercontent.com/17445847/145783523-f4553729-9f03-44a8-a7cc-782aadf67b50.MP4>

<https://user-images.githubusercontent.com/61866546/147812864-52fdde74-602f-4f64-ac05-4d34cc58aa79.mp4>
## 速度PK

| 测试信息 | 内容                                      |
| -------- | ----------------------------------------- |
| 系统     | Windows 11                                |
| 处理器   | Intel(R) Core(TM) i9-10900K CPU @ 3.70GHz |
| 显卡     | NVIDIA GeForce RTX 2070 SUPER             |
| RAM      | 32.0 GB                                   |



源文件： 任务：放大2倍

<https://cdn.jsdelivr.net/gh/Baiyuetribe/paper2gui@main/docs/video/vsr/onepiece_demo.mp4>

| 算法           | 超分耗时 | 转换质量 |
| -------------- | -------- | -------- |
| waifu2x        | 4.30秒   | 差       |
| RealESRGAN     | 8.6秒    | 优       |
| RealCugan      | 17.01秒  | 优       |
| RealESRGAN(v2) | 21.91秒  | 优       |
| RealSR         | -        | -        |

实际效果：

<https://raw.githubusercontent.com/Baiyuetribe/paper2gui/main/docs/video/vsr/onepiece_demo_waifu_2X_0429182311.mp4>
<https://raw.githubusercontent.com/Baiyuetribe/paper2gui/main/docs/video/vsr/onepiece_demo_realcugan_2X_0429181825.mp4>
<https://raw.githubusercontent.com/Baiyuetribe/paper2gui/main/docs/video/vsr/onepiece_demo_RealESRGANv2_2X_0429182058.mp4>


## 创意PK



## 参考

- [nagadomi/waifu2x](https://github.com/nagadomi/waifu2x)
- [jixiaozhong/RealSR](https://github.com/jixiaozhong/RealSR)
- [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
- [bilibili/ailab](https://github.com/bilibili/ailab/tree/main/Real-CUGAN)
- [Naive-ui](https://www.naiveui.com/zh-CN/os-theme)
- [wailsapp/wails](https://github.com/wailsapp/wails)
- [Baiyuetribe/paper2gui](https://github.com/Baiyuetribe/paper2gui)