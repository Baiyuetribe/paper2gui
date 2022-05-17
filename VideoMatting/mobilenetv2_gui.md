# MobileNetV2-GUI 视频抠图工具

【快捷入口：[综述](readme.md) # [MODNet](modnet_gui.md) # [MobileNetV2](mobilenetv2_gui.md) 】

## 软件截图：

![](../docs/images/mobilenetv2_gui.png)

## 效果演示：

![](https://github.com/ZHKKKe/MODNet/raw/master/doc/gif/homepage_demo.gif)

## 软件特点

- 操作简单、即开即用
- 支持任意大小图片或视频
- 软件体积小，轻量便捷
- 支持vulkan GPU加速，低显存消耗
- 抠图速度超级快
- 不消耗硬盘空间、纯内存效率提升26%
- 支持Windows(Mac、Linux后续补全)

## 使用场景：

- 任意需要视频抠图的场景，告别人工绿幕，节省时间

## 案例展示

### 视频处理

| 测试信息 | 内容                                      |
| -------- | ----------------------------------------- |
| 系统     | Windows 11                                |
| 处理器   | Intel(R) Core(TM) i9-10900K CPU @ 3.70GHz |
| 显卡     | NVIDIA GeForce RTX 2070 SUPER             |
| RAM      | 32.0 GB                                   |

<!-- 源文件： 以demo.mp4为例，传统硬盘模式下：FPS为23.98，视频大小为1920*1080，视频时长为14s；在上述环境下，抠图总耗时：17.3s，平均FPS：37.9 -->
源文件： 以demo.mp4为例，FPS为23.98，视频大小为1920*1080，视频时长为14s；在上述环境下，抠图总耗时：9.05s，平均FPS：46.85

## 重要突破：

新应用使用内存模式，不再依赖大量的硬盘空间，提高了抠图效率，相比上个版本提升26.8%。

## 下载地址：

方式1：[GitHub](https://github.com/Baiyuetribe/paper2gui/releases/tag/Published)
方式2：[阿里云盘](https://www.aliyundrive.com/s/2b4hyudGkni)

## 使用反馈：

请前往：https://github.com/Baiyuetribe/paper2gui/issues

## 参考
- [d-li14/mobilenetv2.pytorch](https://github.com/d-li14/mobilenetv2.pytorch)
- [Naive-ui](https://www.naiveui.com/zh-CN/os-theme)
- [wailsapp/wails](https://github.com/wailsapp/wails)
- [Baiyuetribe/paper2gui](https://github.com/Baiyuetribe/paper2gui)