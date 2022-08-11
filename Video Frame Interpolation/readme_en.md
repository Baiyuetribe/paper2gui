# Video Frame Interpolation

[Quick entry: [Overview](readme.md) # [Rife](rife-gui.md) # [DAIN](dain-gui.md)]

## Developer Comments:
> As of April 2022, since the emergence of the rife algorithm for video frame supplementation, there has been no new breakthrough to replace it. The rife algorithm has become the only mainstream with its fast speed, free frame-filling and basically satisfactory pinning effect.
## Introduction

When playing games, we all pay attention to a technical indicator, that is, the frame rate (FPS), which means the number of frames per second (frames per second, fps). Generally speaking, the higher the frame rate, the smoother the picture will be. For example, the game "Genshin Impact" provides two frame rates on the mobile side, 30fps and 60 fps, to choose from. Needless to say, with hardware support, 60 fps looks much smoother than 30 fps.

So, what about watching a movie? In fact, standard movie footage is played at 24 fps. Although 24 fps might not even sound as high as 30 fps, in general, even at 24 fps, we didn't feel very unsmooth due to the more pronounced and realistic motion blur in movies. This means that most of the movies and TV series we usually see are played at 24 fps (especially on computers and TVs).

In terms of technical implementation, the video is re-divided into pictures, and then the AI ​​algorithm is used to regenerate a picture between the two pictures before and after, and so on, the entire picture folder is processed, and finally recombined into a video.


Video supplementary frames are especially suitable for sports scenes, and ordinary static scenes have basically no effect.

## Demonstration of Tool:

| Original low frame rate | After frame supplementation |
| -------------------------------- | ---------------- ---------------- |
| ![](../docs/video/guailing0.gif) | ![](../docs/video/guailing1.gif) |

## Speed ​​PK

- rife VS dain (rife wins)

## Creative PK

- How to generate a small dynamic video from two pictures with huge differences? According to the rife algorithm infinitely complementing frames, it seems that it can be done!

## Changelog

- 2022-06-12 Remove the classic rife-gui (hard disk killer) and upgrade to the memory version of rife-gui, bid farewell to the traditional two hard disk read and write, and increase the speed by 30%.

## References: 

- [hzwer/arXiv2021-RIFE](https://github.com/hzwer/arXiv2021-RIFE)
- [nihui/rife-ncnn-vulkan](https://github.com/nihui/rife-ncnn-vulkan)
- [Naive-ui](https://www.naiveui.com/zh-CN/os-theme)
- [wailsapp/wails](https://github.com/wailsapp/wails)
- [Baiyuetribe/paper2gui](https://github.com/Baiyuetribe/paper2gui)