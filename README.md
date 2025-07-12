# HighPorn 视频链接提取（另存为 MP4 格式）

> 🛠 一款适用于 [highporn.net](https://highporn.net/video/...) 视频页面的 Tampermonkey 脚本，自动提取当前视频播放地址，生成“另存为”提示按钮，方便用户下载 MP4 视频。

## 📌 功能介绍

- 自动检测页面中 `<video class="jw-video">` 元素
- 提取 `.src` 视频直链
- 插入提示区域，显示视频链接与下载提示按钮
- 模拟 `<a>` 点击触发下载
- 防止重复插入 UI

## 🖥️ 使用方法

1. 安装 [Tampermonkey](https://greasyfork.org/zh-CN/scripts/541527-highporn-%E8%A7%86%E9%A2%91%E9%93%BE%E6%8E%A5%E6%8F%90%E5%8F%96-%E5%8F%A6%E5%AD%98%E4%B8%BAmp4%E6%A0%BC%E5%BC%8F) 插件
2. 添加本脚本
3. 访问 `https://highporn.net/video/*` 视频页面
4. 页面加载后会自动插入下载提示

## 📂 插件界面示例

```
🎬 视频链接已检测，可手动下载...
[视频链接] [请右键单击链接另存为...]
```

## 📄 元数据头部

见 `highporn-download.user.js` 文件开头

## 🔗 安装链接（用于 Raw 安装）

```
https://github.com/catmanin/HighPorn-mp4-download/blob/main/highporn-download.user.js
```
# HighPorn 视频链接提取

下面是功能预览截图：

![功能预览](https://raw.githubusercontent.com/catmanin/HighPorn-mp4-download/refs/heads/main/%E5%8A%9F%E8%83%BD%E9%A2%84%E8%A7%88.png)

如上图所示，脚本会在视频页面自动插入下载链接和提示按钮。

## 🧾 LICENSE

MIT
