# 陈梓琦个人作品集 | Chen Ziqi Portfolio

一个现代化、高端的个人作品集网站，包含首页和独立的作品详情页面。

## ✨ 特性

- 🎨 现代简约设计风格，蓝绿色主题
- 👤 个人头像和简介展示
- 📱 响应式设计，支持各种设备
- 🖼️ 作品集网格布局，点击卡片查看作品详情
- 📸 每个作品独立详情页，支持多图展示
- ✨ 流畅的动画效果和交互体验
- 🚀 快速加载，性能优化

## 📁 项目结构

```
chenziqi-portfolio/
├── index.html              # 主页（包含所有作品卡片）
├── project1.html           # 作品1详情页：智能物联网机器人
├── project2.html           # 作品2详情页：情感交互装置
├── project3.html           # 作品3详情页：3D打印创新设计
├── project4.html           # 作品4详情页：数据可视化平台
├── project5.html           # 作品5详情页：智能健康监测手环
├── project6.html           # 作品6详情页：沉浸式虚拟展览
├── style.css               # 统一样式文件
├── README.md               # 项目说明
└── images/                 # 图片资源
    ├── avatar.jpg          # 个人头像（建议300x300px）
    └── projects/           # 项目图片文件夹
        ├── project1/       # 作品1图片
        │   ├── cover.jpg   # 封面图
        │   ├── image1.jpg  # 详情图1
        │   ├── image2.jpg  # 详情图2
        │   ├── image3.jpg  # 详情图3
        │   └── image4.jpg  # 详情图4
        ├── project2/       # 作品2图片
        │   ├── cover.jpg
        │   ├── image1.jpg
        │   ├── image2.jpg
        │   └── image3.jpg
        ├── project3/       # 作品3图片
        │   ├── cover.jpg
        │   ├── image1.jpg
        │   ├── image2.jpg
        │   ├── image3.jpg
        │   └── image4.jpg
        ├── project4/       # 作品4图片
        │   ├── cover.jpg
        │   ├── image1.jpg
        │   ├── image2.jpg
        │   └── image3.jpg
        ├── project5/       # 作品5图片
        │   ├── cover.jpg
        │   ├── image1.jpg
        │   ├── image2.jpg
        │   ├── image3.jpg
        │   └── image4.jpg
        └── project6/       # 作品6图片
            ├── cover.jpg
            ├── image1.jpg
            ├── image2.jpg
            ├── image3.jpg
            └── image4.jpg
```

## 🚀 快速开始

### 本地预览

直接双击 `index.html` 文件即可在浏览器中打开查看。

### 部署到 GitHub Pages

1. **推送代码到 GitHub**
```bash
git add .
git commit -m "Update portfolio with project detail pages"
git push origin main
```

2. **启用 GitHub Pages**
   - 进入 GitHub 仓库页面
   - 点击 **Settings** → **Pages**
   - Source 选择 **main** 分支
   - Folder 选择 **/(root)**
   - 点击 **Save**

3. **访问网站**
   - 等待1-2分钟
   - 访问：`https://cziqi9307-byte.github.io/chenziqi-portfolio/`

## 🎨 自定义内容

### 修改个人信息
编辑 `index.html` 文件：
- 第48-51行：姓名和标题
- 第52-54行：个人简介
- 第290-310行：联系方式

### 添加/修改作品

#### 方法1：修改现有作品
1. 编辑对应的 `projectX.html` 文件（X为1-6）
2. 修改标题、描述、技术栈等内容
3. 替换 `images/projects/projectX/` 中的图片

#### 方法2：添加新作品
1. 复制 `project1.html` 并重命名为 `project7.html`
2. 修改文件内容（标题、描述等）
3. 在 `index.html` 中添加新的作品卡片
4. 创建 `images/projects/project7/` 文件夹并添加图片

### 更换头像
将您的头像照片保存为 `images/avatar.jpg`（建议尺寸：300x300px）

### 修改颜色主题
在 `style.css` 的 `:root` 部分修改颜色变量：
```css
--primary-blue: #7BA7BC;    /* 主蓝色 */
--primary-green: #8FAE8A;   /* 主绿色 */
--accent-rose: #C9A9A6;     /* 辅助色 */
```

## 📸 图片说明

### 图片要求
- **格式**：JPG 或 PNG
- **质量**：建议压缩后上传，保持文件大小在500KB以内
- **尺寸**：
  - 头像：300x300px
  - 作品封面：800x600px
  - 作品详情图：1200x800px

### 如果没有图片
网站会自动显示渐变色背景作为占位符，不影响正常使用。

## 🌟 功能特点

### 首页功能
- ✅ 个人头像展示（带旋转光环动画）
- ✅ 个人简介和技能展示
- ✅ 作品卡片网格布局
- ✅ 点击卡片跳转到作品详情页
- ✅ 平滑滚动导航
- ✅ 响应式设计

### 作品详情页功能
- ✅ 返回按钮（回到首页作品集）
- ✅ 作品标题和简介
- ✅ 技术栈标签展示
- ✅ 主图展示区（大图）
- ✅ 缩略图切换（点击切换主图）
- ✅ 项目详细介绍
- ✅ 核心功能列表
- ✅ 技术架构展示
- ✅ 项目成果统计
- ✅ 上一个/下一个作品导航

## 📱 浏览器支持

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 移动浏览器

## 🛠️ 技术栈

- **HTML5** - 语义化标签
- **CSS3** - 现代样式和动画
- **JavaScript** - 交互功能
- **Font Awesome** - 图标库
- **Google Fonts** - 字体

## 📄 许可证

MIT License

---

Made with ❤️ by 陈梓琦
