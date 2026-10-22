# MediaPipe 微表情识别 POC

基于 MediaPipe Face Landmarker 的前端实时微表情识别原型。

## 功能
- 浏览器端全本地运行（MediaPipe Face Landmarker + GPU delegate）
- 实时摄像头采集（getUserMedia / WebRTC）
- EMA 平滑滤波
- 简单 AU 映射（AU1/2/4/5/6/12/15/26/45）
- 规则式主导情绪判断
- AU 条形图 + 关键点示意

## 使用
1. 用浏览器直接打开 `index.html`（需 HTTPS 或 localhost）
2. 点击「启动摄像头」
3. 正对镜头、光线充足

## 下一步
- Vue + Web Worker 重构
- 接入 @meetcore/expression
- 微表情时序窗口检测

## 运行
```bash
# 可选：用 live-server 或任意静态服务器
npx live-server .
```
