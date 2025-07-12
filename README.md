# HighPorn 视频链接提取（另存为 MP4 格式）  
HighPorn Video Link Extractor (Save as MP4 Format)

> 🛠 一款适用于 [highporn.net](https.highporn.net/video/...) 视频页面的 Tampermonkey 脚本，  
> 自动提取当前视频播放地址，生成“另存为”提示按钮，方便用户下载 MP4 视频。  
>  
> 🛠 A Tampermonkey userscript for [highporn.net](https.highporn.net/video/...) video pages,  
> automatically extracts the current video URL and inserts a “Save As” prompt button to facilitate MP4 downloads.

---

## 📌 功能介绍 | Features

- 自动检测页面中 `<video class="jw-video">` 元素  
  Auto detects `<video class="jw-video">` element on the page  
- 提取 `.src` 视频直链  
  Extracts the direct video URL from `.src`  
- 插入提示区域，显示视频链接与下载提示按钮  
  Inserts a UI area showing video link and a download prompt button  
- 模拟 `<a>` 点击触发下载  
  Simulates `<a>` click to trigger download  
- 防止重复插入 UI  
  Prevents duplicate UI insertions  

---

## 🖥️ 使用方法 | Usage

1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 插件  
   Install the [Tampermonkey](https://www.tampermonkey.net/) extension  
2. 添加本脚本  
   Add this userscript  
3. 访问 `https://highporn.net/video/*` 视频页面  
   Visit video pages on `https://highporn.net/video/*`  
4. 页面加载后会自动插入下载提示  
   Download prompt will be automatically inserted after page load  

---

## 📂 插件界面示例 | UI Example
🎬 视频链接已检测，可手动下载...[视频链接] [请右键单击链接另存为...]
---

## 📄 元数据头部 | Metadata Header

见 `highporn-download.user.js` 文件头部  
See the header in `highporn-download.user.js`

---

## 🔗 安装链接 | Installation Link (Raw)
https://github.com/catmanin/HighPorn-mp4-download/blob/main/highporn-download.user.js

---

# HighPorn 视频链接提取功能预览  
HighPorn Video Link Extractor Preview

下面是功能预览截图：  
Below is the feature preview screenshot:

![功能预览](https://raw.githubusercontent.com/catmanin/HighPorn-mp4-download/refs/heads/main/%E5%8A%9F%E8%83%BD%E9%A2%84%E8%A7%88.png)

如上图所示，脚本会在视频页面自动插入下载链接和提示按钮。  
As shown above, the script automatically inserts a download link and prompt button on the video page.

---

## 🧾 LICENSE

MIT
