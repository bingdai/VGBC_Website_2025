# 温哥华浸信会福音堂 - 网站资源 / VGBC Website Assets

## 文件夹结构 / Folder Structure

### `/assets/logos/`
教会标志和图标 / Church logos and icons
- `logo.png` - 主要标志 (建议尺寸: 400x200px)
- `logo-white.png` - 白色标志 (用于深色背景)
- `favicon.ico` - 网站图标 (32x32px)
- `favicon-192.png` - 移动设备图标 (192x192px)

### `/assets/images/`
一般图片 / General images
- `hero-bg.jpg` - 首页背景图 (建议尺寸: 1920x1080px)
- `church-exterior.jpg` - 教会外观照片
- `church-interior.jpg` - 教会内部照片

### `/assets/photos/`
活动和人物照片 / Event and people photos
- `pastor-hong.jpg` - 洪牧师照片
- `worship-service.jpg` - 崇拜聚会照片
- `bible-study.jpg` - 查经班照片
- `church-events/` - 教会活动照片子文件夹

### `/assets/documents/`
文档和资料 / Documents and materials
- `bulletin.pdf` - 周报
- `calendar.pdf` - 活动日历
- `beliefs.pdf` - 信仰声明

## 图片优化建议 / Image Optimization Guidelines

### 网页显示 / Web Display
- **格式**: JPG (照片), PNG (标志/透明背景), WebP (现代浏览器)
- **文件大小**: 尽量小于 500KB
- **移动端优化**: 考虑不同屏幕尺寸

### 建议尺寸 / Recommended Sizes
- **标志**: 400x200px (2:1 比例)
- **首页横幅**: 1920x1080px (16:9 比例)
- **卡片图片**: 800x600px (4:3 比例)
- **人物照片**: 400x400px (正方形)

## 如何上传 / How to Upload

1. 将图片文件复制到相应文件夹
2. 确保文件名使用英文，无空格 (使用 `-` 或 `_`)
3. 在 HTML 中更新图片路径
4. 提交到 Git 并部署

## 示例 / Examples

```html
<!-- 教会标志 -->
<img src="assets/logos/logo.png" alt="温哥华浸信会福音堂">

<!-- 首页背景 -->
<div style="background-image: url('assets/images/hero-bg.jpg')">

<!-- 牧师照片 -->
<img src="assets/photos/pastor-hong.jpg" alt="洪牧师">
```