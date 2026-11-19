# Christmas Tree Touch & Gesture

一个由 Three.js 和 MediaPipe 构建的 3D 粒子圣诞树页面，支持触控、摄像头手势和照片上传，并针对微信内置浏览器做了入口与安全区适配。

## 微信访问

直接打开：

https://shaoyesy.github.io/christmas-tree-touch-gesture/

首次轻触页面即可进入圣诞树并尝试开启背景音乐。微信 WebView 若不支持摄像头权限，触控、旋转和照片上传仍然可以正常使用。

## 页面

- [打开圣诞树页面](index.html)
- [背景音乐](audio/christmas.mp3)

## 本地运行

由于摄像头权限和浏览器模块限制，建议通过本地 Web 服务器打开：

```powershell
python -m http.server 8000
```

然后访问：

```text
http://localhost:8000/
```

## 来源

页面来源于 [ACE5447180/gesture-Christmas_tree-3d_with_photo](https://github.com/ACE5447180/gesture-Christmas_tree-3d_with_photo)，遵循仓库中的 MIT License。
