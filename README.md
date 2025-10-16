# Moncici - 个人主页

> Web3 Builder | 全栈开发者 | DeFi策略师

这是 Moncici 的个人主页网站，展示了我的技能、经历、项目和文章。

## 🌟 特性

- **现代化设计**: 采用渐变色、毛玻璃效果和流畅动画
- **响应式布局**: 完美适配桌面端、平板和移动设备
- **平滑滚动**: 优雅的页面导航体验
- **交互动画**: 丰富的页面元素动画效果
- **SEO优化**: 良好的语义化HTML结构

## 📁 项目结构

```
profile/
├── index.html      # 主页面
├── styles.css      # 样式文件
├── script.js       # 交互脚本
└── README.md       # 说明文档
```

## 🚀 快速开始

### 本地运行

1. 克隆或下载项目到本地
2. 直接在浏览器中打开 `index.html` 文件

或者使用本地服务器（推荐）:

```bash
# 使用 Python
python -m http.server 8000

# 使用 Node.js (http-server)
npx http-server

# 使用 PHP
php -S localhost:8000
```

然后在浏览器中访问 `http://localhost:8000`

## 🎨 页面结构

### 主要部分

1. **导航栏** - 固定顶部导航，支持平滑滚动
2. **Hero区域** - 个人介绍、关键统计数据和社交链接
   - 14K+ X粉丝
   - 1150+ YouTube订阅者
   - 3000+ Discord社区成员
   - 10+年经验
3. **关于我** - 个人简介和背景介绍
4. **核心技能** - 社区运营（包含YouTube运营）、Web3技术、传统技术三大板块
5. **经历** - 时间轴展示工作和项目经历
6. **核心项目** - 专注DeFi量化交易与区块链技术
   - **Perp** (精选): 网格交易策略 - 54 ⭐, 28 Forks
     - 支持 Bumpin 和 Backpack 交易所
     - 动态网格策略、实时监控、安全加密
   - **Kronos**: AI金融模型 - 46 ⭐, 5 Forks
     - 金融市场语言基础模型
     - AI/ML驱动的市场分析
   - **Quant**: 量化交易系统
     - 完整的量化交易框架
     - 策略回测、实盘交易、数据分析
   - **Funding Rate**: 资金费率监控
     - 实时监控多交易所资金费率
     - 捕捉套利机会
7. **精选视频** - YouTube视频嵌入展示
   - 重点展示：[Web3 技术深度解析](https://www.youtube.com/watch?v=VRtrbAQ4rs4&t=66s)
   - 响应式视频播放器
   - 直达YouTube链接
8. **精选文章** - X (Twitter) 平台的6篇重点文章
   - 币圈套利：理论篇
   - 无风险资金费率套利系统
   - Cookie首发项目Spark积分空投教程
   - Eclipse $BITZ 挖矿教程（Windows版本）
   - Gensyn节点运行教程（融资4950万美元）
   - 5英镑英国保号卡教程
9. **联系方式** - Email、X、YouTube、GitHub、Discord链接

## 💻 技术栈

- **HTML5** - 语义化结构
- **CSS3** - 现代化样式
  - CSS Grid & Flexbox
  - CSS变量
  - 渐变和阴影
  - 动画和过渡效果
- **Vanilla JavaScript** - 纯JS实现交互
  - Intersection Observer API
  - 平滑滚动
  - 移动端菜单
  - 动画效果

## 🎯 核心功能

### 导航功能
- 固定顶部导航栏
- 滚动时背景变化
- 移动端汉堡菜单
- 当前页面高亮

### 动画效果
- 页面元素淡入动画
- 悬停效果
- 平滑过渡
- 统计数字动画

### 响应式设计
- 桌面端 (1200px+)
- 平板端 (768px - 1199px)
- 移动端 (< 768px)

## 📝 自定义指南

### 修改个人信息

编辑 `index.html` 中的相关内容：

```html
<!-- 修改标题 -->
<h1 class="hero-title">
    <span class="gradient-text">你的名字</span>
</h1>

<!-- 修改联系邮箱 -->
<a href="mailto:your.email@example.com">
```

### 更新项目展示

在 `index.html` 的项目部分添加或修改项目卡片：

```html
<div class="project-card">
    <div class="project-header">
        <div class="project-icon">🚀</div>
    </div>
    <h3>项目名称</h3>
    <p class="project-description">项目描述...</p>
    <!-- 更多内容 -->
</div>
```

### 修改配色方案

编辑 `styles.css` 中的CSS变量：

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    /* 修改其他颜色 */
}
```

### 添加文章

在 `index.html` 的文章部分添加新的文章卡片：

```html
<div class="article-card">
    <div class="article-header">
        <span class="article-category">分类</span>
        <span class="article-date">日期</span>
    </div>
    <h3>文章标题</h3>
    <p>文章摘要...</p>
    <a href="链接" target="_blank" class="article-link">阅读更多 →</a>
</div>
```

## 🌐 部署

### GitHub Pages

1. 将代码推送到GitHub仓库
2. 进入仓库的 Settings > Pages
3. 选择分支并保存
4. 访问 `https://yourusername.github.io/repository-name`

### Vercel

```bash
# 安装 Vercel CLI
npm i -g vercel

# 部署
vercel
```

### Netlify

1. 将项目拖放到 Netlify 网站
2. 或连接GitHub仓库自动部署

## 📱 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge
- 移动端浏览器

## 📄 许可证

本项目仅供个人使用。如需商用，请联系作者。

## 📧 联系方式

- **Email**: moncici2119@gmail.com
- **X (Twitter)**: [@moncici_is_girl](https://x.com/moncici_is_girl) - 14K+ 粉丝
- **YouTube**: [@moncici_girl](https://www.youtube.com/@moncici_girl) - 1150+ 订阅者
  - 精选视频：[Web3 技术深度解析](https://www.youtube.com/watch?v=VRtrbAQ4rs4&t=66s)
- **GitHub**: [@moncici007](https://github.com/moncici007) - 45个仓库
- **Discord**: [加入社区](https://discord.com/channels/1215119263480938496/1360265935180791918) - 3000+ 成员

## 🙏 致谢

感谢所有支持和关注我的朋友们！

---

Built with ❤️ for Web3 Community

# profile
