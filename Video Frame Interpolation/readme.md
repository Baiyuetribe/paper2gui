# 视频补帧

【快捷入口：[综述](readme.md) # [Rife](rife-gui.md) # [DAIN](dain-gui.md)】

## 开发者评价
> 截至2022年4月，视频补帧自rife算法出现后，暂未有新突破可替代。rife算法以其速度快、自由补帧和基本满意的插针效果，成为唯一主流。
## 简介

玩游戏的时候，我们都会关注一个技术指标，那就是帧率（Frame rate），它的意义在于每秒钟画面出现的帧数（frames per second, fps）。一般来说，帧数越高，画面就越流畅。比如游戏《原神》在移动端提供两档帧率，30fps和 60 fps，可供选择，无须多言，在硬件支持的情况下，60 fps 要比 30 fps 看起来流畅很多。

那么，看电影呢？其实，标准的电影画面是以 24 fps 进行播放的。尽管听起来 24 fps 甚至还没有 30 fps 高，但是一般来说，由于电影中的动态模糊效果更为明显、真实，所以即使是 24 fps，我们也不会觉得非常不流畅。这也就是说，我们平常看到的大多数电影、电视剧，都是以 24 fps 进行播放的（尤其是在电脑、电视上）。

技术实现上，把视频重新分割成一张张图片，然后前后两张图片之间利用AI算法重新生成一张图，依次类推，处理整个图片文件夹，最后再重新组合成视频。


视频补帧特别适合运动类场景，普通静态场景基本无效果。

## 效果演示：

| 原始低帧率                       | 补帧后                           |
| -------------------------------- | -------------------------------- |
| ![](../docs/video/guailing0.gif) | ![](../docs/video/guailing1.gif) |

## 速度PK

- rife VS dain (rife完胜)

## 创意PK

- 如何让两张差异巨大的图片，生成一段动态小视频呢？根据rife算法无限补帧，似乎可以做到！

## 变更日志

- 2022-06-12 下架经典的rife-gui(硬盘杀手)，升级为内存版rife-gui，告别传统的两次硬盘读写，速度提升30%。

## 参考

- [hzwer/arXiv2021-RIFE](https://github.com/hzwer/arXiv2021-RIFE)
- [nihui/rife-ncnn-vulkan](https://github.com/nihui/rife-ncnn-vulkan)
- [Naive-ui](https://www.naiveui.com/zh-CN/os-theme)
- [wailsapp/wails](https://github.com/wailsapp/wails)
- [Baiyuetribe/paper2gui](https://github.com/Baiyuetribe/paper2gui)
