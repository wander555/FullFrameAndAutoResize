# FullFrameAndAutoResize
根据背景图片的大小，自适应屏幕和分辨率

## 关键思路
- 在一个主页中嵌入一个iframe，iframe放入目标页面
- 监听浏览器的尺寸，改变主页body的大小的同时，改变iframe的大小
