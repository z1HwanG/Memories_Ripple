---
title: "关于"
aliases: ["about-me"]
author: "z1HwanG"
comments: false
readingTime: false
---

<div class="about-header">
  <div class="about-header-overlay"></div>
  <div class="about-header-content">
    <h1>关于我的博客</h1>
    <p>记录成长，分享生活与技术的点滴</p>
  </div>
</div>

## 👋 关于我

嗨，我是 z1HwanG，一名热爱技术与创作的博主。

- 🔭 目前正在研究
- 🌱 不断学习新知识，热爱分享所学所思
- 🎯 希望通过文字记录成长，也希望与更多志同道合的朋友交流
- 🎸 爱好广泛，喜欢音乐、阅读和户外活动

> 「行到水穷处，坐看云起时」 —— 王维

<div class="divider"><span>✦</span><span>✦</span><span>✦</span></div>

## 💻 关于本站

本站于2024年创建，使用 [Hugo](https://gohugo.io/) 构建，主题是 [Stack](https://github.com/CaiJimmy/hugo-theme-stack)。

### 本站特色

- 🚀 极速加载体验
- 🔍 支持全文搜索功能
- 💬 选择性开启文章评论（基于GitHub Discussions）
- 📱 完美适配移动端与桌面端
- 🌓 支持深色/浅色模式切换

### 内容分类

本站主要包含以下几类内容：
- 技术分享与教程
- 读书笔记与思考
- 生活随笔
- 转载优质文章



## 🔧 技术栈

- **前端**: HTML, CSS, JavaScript
- **框架**: Hugo, Stack主题
- **部署**: GitHub Pages
- **评论**: Giscus (基于GitHub Discussions)
- **搜索**: Pagefind

<div class="divider"><span>✦</span><span>✦</span><span>✦</span></div>

## 🌈 友情链接

欢迎交换友链，要求如下：
- 网站内容健康积极
- 网站能够正常访问
- 有一定的原创内容

如果您希望添加友链，请通过邮件联系我，格式如下：
- 网站名称
- 网站链接
- 网站Logo
- 网站描述（一句话）

<div class="divider"><span>✦</span><span>✦</span><span>✦</span></div>

## 📫 联系方式

- ✉️ Email: z1hwang@163.com
- 🐱 GitHub: [https://github.com/z1HwanG](https://github.com/z1HwanG/Blog_Test)

---

> 感谢您访问我的博客，希望这里的内容能给您带来一些启发或帮助！

<style>
/* 页面头部样式 */
.about-header {
  position: relative;
  width: 100%;
  height: 280px;
  background-image: url('/img/1.jpg');
  background-size: cover;
  background-position: center;
  margin-bottom: 40px;
  border-radius: 10px;
  overflow: hidden;
}
.about-header-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.4);
}
.about-header-content {
  position: absolute;
  bottom: 30px;
  left: 30px;
  color: #fff;
  z-index: 2;
}
.about-header-content h1 {
  margin: 0;
  font-size: 2.5rem;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
}
.about-header-content p {
  margin: 10px 0 0;
  font-size: 1.2rem;
  opacity: 0.9;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.5);
}

/* 分隔符样式 */
.divider {
  display: flex;
  align-items: center;
  text-align: center;
  margin: 30px 0;
  color: var(--accent-color);
  opacity: 0.6;
}
.divider span {
  margin: 0 10px;
}
.divider::before,
.divider::after {
  content: "";
  flex: 1;
  border-bottom: 1px solid var(--border-color);
}

/* 时间线样式 */
.timeline {
  position: relative;
  max-width: 100%;
  margin: 30px 0;
}
.timeline::after {
  content: '';
  position: absolute;
  width: 4px;
  background-color: var(--card-background);
  border-radius: 5px;
  top: 0;
  bottom: 0;
  left: 15px;
  margin-left: -2px;
}
.timeline-item {
  padding: 10px 40px;
  position: relative;
  margin-bottom: 20px;
}
.timeline-item::before {
  content: '';
  position: absolute;
  width: 20px;
  height: 20px;
  left: 5px;
  background-color: var(--accent-color);
  border: 4px solid var(--card-background);
  border-radius: 50%;
  z-index: 1;
  top: 15px;
}
.timeline-date {
  font-weight: bold;
  color: var(--accent-color);
  margin-bottom: 5px;
}
.timeline-content {
  padding: 15px;
  background-color: var(--card-background);
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}
.timeline-content h4 {
  margin-top: 0;
  color: var(--card-text-color-main);
}
.timeline-content p {
  margin-bottom: 0;
  color: var(--card-text-color-secondary);
}

/* 友情链接样式 */
.friend-links-wrap {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  margin: 20px 0;
}
.friend-link-item {
  width: calc(50% - 8px);
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  border-radius: 10px;
  transition: all 0.3s;
}
.friend-link-item:hover {
  transform: translateY(-3px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}
.friend-link-link {
  text-decoration: none !important;
}
.friend-link-content {
  display: flex;
  padding: 15px;
  align-items: center;
}
.friend-link-avatar {
  width: 50px;
  height: 50px;
  margin-right: 15px;
  border-radius: 50%;
  overflow: hidden;
  flex-shrink: 0;
}
.friend-link-avatar img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.friend-link-name {
  font-weight: bold;
  margin-bottom: 5px;
}
.friend-link-description {
  font-size: 0.9em;
  color: #666;
  opacity: 0.8;
}
@media (max-width: 768px) {
  .friend-link-item {
    width: 100%;
  }
  .about-header {
    height: 200px;
  }
  .about-header-content h1 {
    font-size: 1.8rem;
  }
  .about-header-content p {
    font-size: 1rem;
  }
}
</style>
