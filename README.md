# 成果中期 PDF 网页

这个目录是一个静态网页，可以直接上传到 GitHub Pages、Netlify、Vercel、学校服务器或任意静态网站空间。

## 文件

- `index.html`: 网页入口
- `styles.css`: 页面样式
- `assets/chengguo-zhongqi.pdf`: 本地原 PDF 副本
- `assets/chengguo-zhongqi.base64.txt`: GitHub Pages 使用的 PDF 文本副本

## 本地预览

在这个目录运行：

```powershell
python -m http.server 8765
```

然后打开：

```text
http://localhost:8765/
```

## 发布

把整个 `pdf-web-viewer` 文件夹上传到静态网站空间即可。别人访问 `index.html` 对应的网址，就能在线查看 PDF，并点击右上角按钮下载原文件。
