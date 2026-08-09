# Miller-Theme ❀

一个基于樱花配色设计的 Hexo 个人博客主题，简洁、优雅、响应式。

## 特性

- 🌸 樱花配色设计 - 粉白渐变背景，樱花粉强调色
- 🌓 自适应暗色模式 - 根据系统自动切换明暗主题
- 🌸 樱花飘落动画 - 6 片花瓣动态飘落效果
- 📱 完整移动端适配 - 汉堡菜单 + 响应式布局
- 💻 代码高亮 - 基于 highlight.js，樱花色系语法着色
- 📋 代码复制按钮 - 一键复制代码，支持语言标签
- 🎯 毛玻璃特效 - 精致的模糊背景效果
- ✨ 发光边框 - 文章卡片与代码块的樱花发光效果
- 📁 分类展示 - 优雅的分类菜单
- 🚀 优化性能 - 快速加载和流畅动画

## 安装

```bash
cd your-blog
git clone https://github.com/Miller-Maxim/Miller-Theme.git themes/Miller-Theme
```

在 `_config.yml` 中启用主题：

```yaml
theme: Miller-Theme
```

## 配置

### 代码高亮

在 `_config.yml` 中配置 highlight.js：

```yaml
highlight:
  line_number: false
  auto_detect: false
  tab_replace: ''
  wrap: false
  hljs: true
```

### 主题颜色

主题颜色在 `source/css/style.styl` 的 `:root` 中定义，可自定义修改：

```stylus
:root
    --accent-color: #FF8FA3      // 樱花粉
    --accent-hover: #E91E63      // 悬停深粉
    --petal-color: #FFB7C5       // 花瓣颜色
```

## 目录结构

```
Miller-Theme/
├── layout/
│   ├── layout.ejs       # 主布局模板
│   ├── index.ejs        # 首页模板
│   ├── post.ejs          # 文章详情模板
│   └── _partial/
│       └── pagination.ejs
├── source/
│   ├── css/
│   │   └── style.styl   # 主样式文件
│   └── images/
└── fonts/                # 自定义字体
```

## 许可证

GPL 3.0 - 查看 [LICENSE](LICENSE) 了解详情

## 作者

Miller Maxim - [GitHub](https://github.com/Miller-Maxim)

## 支持

如果你喜欢这个主题，请给它一个 Star ⭐
