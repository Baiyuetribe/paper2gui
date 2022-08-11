# Video Super Resolution

[Quick entry: [Review](readme.md) # [RealESRGAN-RAM](RealESRGAN-GUI-RAM.md) # [RealCugan](RealCugan-GUI.md) # [RealESRGAN](RealESRGAN-GUI.md) # [Waifu2x](waifu2x-gui.md) # [ReslSR](RealSR-GUI.md)]

## Developer Comments:
> As of April 2022, video super-resolution is in full bloom, but it is mainly performing well in the animation field. Among them, RealESGAN, RealCugan and other algorithms have been significantly better than waifu2x.
## Introduction:

The super-resolution technology is derived from the intelligent image magnification technology. All the integrated tools currently support super-resolution magnification of a single image or a single video, such as 720p to 4K.

## Demonstration of tool:

![](../docs/images/styletransfer/iu.jpg)
![](https://github.com/bilibili/ailab/blob/main/Real-CUGAN/demos/title-compare1.png)
![](https://github.com/xinntao/Real-ESRGAN/raw/master/assets/teaser.jpg)
![](https://raw.githubusercontent.com/xinntao/public-figures/master/Real-ESRGAN/cmp_realesrgan_anime_1.png)
![](https://github.com/jixiaozhong/RealSR/blob/master/figures/0935.png)
<https://user-images.githubusercontent.com/17445847/145706977-98bc64a4-af27-481c-8abe-c475e15db7ff.MP4>

<https://user-images.githubusercontent.com/17445847/145707055-6a4b79cb-3d9d-477f-8610-c6be43797133.MP4>

<https://user-images.githubusercontent.com/17445847/145783523-f4553729-9f03-44a8-a7cc-782aadf67b50.MP4>

<https://user-images.githubusercontent.com/61866546/147812864-52fdde74-602f-4f64-ac05-4d34cc58aa79.mp4>
## Speed ​​PK:

| Test Information | Contents |
| -------- | ---------------------------------------- - |
| System | Windows 11 |
| Processor | Intel(R) Core(TM) i9-10900K CPU @ 3.70GHz |
| Graphics Cards | NVIDIA GeForce RTX 2070 SUPER |
| RAM | 32.0 GB |



Source file: Assignment: 2x magnification

<https://cdn.jsdelivr.net/gh/Baiyuetribe/paper2gui@main/docs/video/vsr/onepiece_demo.mp4>

| Algorithm | Time-consuming | Conversion Quality |
| -------------- | -------- | -------- |
| waifu2x | 4.30 seconds | poor |
| RealESRGAN | 8.6 seconds | Excellent |
| RealCugan | 17.01 seconds | Excellent |
| RealESRGAN(v2) | 21.91 seconds | Excellent |
| RealSR | - | - |

actual effect:

<https://raw.githubusercontent.com/Baiyuetribe/paper2gui/main/docs/video/vsr/onepiece_demo_waifu_2X_0429182311.mp4>
<https://raw.githubusercontent.com/Baiyuetribe/paper2gui/main/docs/video/vsr/onepiece_demo_realcugan_2X_0429181825.mp4>
<https://raw.githubusercontent.com/Baiyuetribe/paper2gui/main/docs/video/vsr/onepiece_demo_RealESRGANv2_2X_0429182058.mp4>


## Creative PK:



## References:

- [nagadomi/waifu2x](https://github.com/nagadomi/waifu2x)
- [jixiaozhong/RealSR](https://github.com/jixiaozhong/RealSR)
- [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)
- [bilibili/ailab](https://github.com/bilibili/ailab/tree/main/Real-CUGAN)
- [Naive-ui](https://www.naiveui.com/zh-CN/os-theme)
- [wailsapp/wails](https://github.com/wailsapp/wails)
- [Baiyuetribe/paper2gui](https://github.com/Baiyuetribe/paper2gui)