# 🌟 肖林峰 - 个人在线简历

一个具有高级感的个人在线简历网页，纯 HTML/CSS/JS 实现，零依赖，可直接部署到 GitHub Pages。

## ✨ 特性

- 🎨 **深色主题** — 毛玻璃效果 + 渐变色彩，科技感十足
- 📱 **响应式设计** — 完美适配手机、平板、桌面
- ✍️ **打字机效果** — Hero 区域动态展示个人标签
- 🎭 **滚动动画** — 基于 Intersection Observer 的流畅渐入效果
- 📊 **技能可视化** — 进度条动画 + 标签云展示
- ⏱️ **时间线布局** — 教育背景清晰呈现
- 🚀 **零依赖** — 无需任何框架或构建工具

## 🚀 部署到 GitHub Pages

### 方法一：通过 GitHub 网页操作

1. 创建一个新的 GitHub 仓库（如 `resume`）
2. 将本项目所有文件上传到仓库
3. 进入仓库 → **Settings** → **Pages**
4. **Source** 选择 `Deploy from a branch`
5. **Branch** 选择 `main`，文件夹选择 `/ (root)`
6. 点击 **Save**
7. 等待几分钟，访问 `https://你的用户名.github.io/resume/`

### 方法二：通过命令行

```bash
# 初始化 Git 仓库
git init
git add .
git commit -m "feat: 初始化个人简历网页"

# 关联远程仓库
git remote add origin https://github.com/你的用户名/resume.git
git branch -M main
git push -u origin main
```

然后在 GitHub 仓库设置中开启 Pages 即可。

## 📝 自定义修改

### 修改个人信息

打开 `index.html`，找到对应位置修改：

- **姓名**：搜索 `肖林峰` 替换
- **教育背景**：搜索 `XX 大学`、`XX 专业` 替换
- **技能**：修改技能名称和百分比
- **项目经历**：修改项目卡片内容
- **荣誉奖项**：修改奖项列表
- **联系方式**：替换邮箱、GitHub、手机号等

### 添加个人照片

在头像区域找到注释，替换 emoji 为图片：

```html
<!-- 替换这行 -->
👨‍🎓
<!-- 为 -->
<img src="your-photo.jpg" alt="肖林峰">
```

### 修改主题色

在 `:root` CSS 变量中修改颜色：

```css
--accent-1: #6c5ce7;  /* 主色调（紫色） */
--accent-2: #00cec9;  /* 辅助色（青色） */
--accent-3: #fd79a8;  /* 点缀色（粉色） */
```

## 📁 文件结构

```
resume/
├── index.html      # 主页面（所有代码内嵌）
├── README.md       # 项目说明
└── .gitignore      # Git 忽略配置
```

## 📄 License

MIT License
