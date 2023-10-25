### 日常练手

- [canvas画矩形支持拖拽](./src/canvas画矩形支持拖拽.html)
- [canvas视频轮播](./src/canvas视频轮播.html)
  - 存在问题
    - 视频播放时，canvas绘制的视频会闪烁。比较卡顿未想到解决方案
- [canvas视频图片轮播](./src/canvas视频图片轮播.html)
  - 使用工具把[视频转换成图片](https://www.img2go.com/zh/convert-to-jpg)，然后使用canvas绘制图片 
  - 解决视频设置 video.currentTime 导致画面卡顿问题
  - 缺点
    - 视频转换成图片，图片过大，加载时间过长