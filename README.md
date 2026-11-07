# LUM3N · HALFTONE

将图片转换成由自定义文字组成的黑白网点图。纯前端运行，图片不会上传。

## 使用
打开网站，选择图片，输入要重复的文字，选择网点算法和输出行数，点击“生成”。可导出 TXT 字符矩阵或 PNG 图像。

## GitHub Pages
仓库 Settings → Pages → Deploy from a branch → Branch: main → Folder: /(root) → Save。

## 说明
- 默认 1080 行，宽度按原图比例计算。
- 算法：Floyd–Steinberg、Bayer、随机网点。
- 所有处理在浏览器本地完成。
