# 七七的个人网站

一个简洁、现代、响应式的个人网站。

## 技术栈
- 纯 HTML / CSS / JavaScript（无需构建工具）
- 响应式设计，适配手机与桌面
- 平滑滚动、滚动入场动画、移动端菜单

## 目录结构
```
.
├── index.html      # 主页面
├── css/
│   └── style.css   # 样式
├── js/
│   └── main.js     # 交互脚本
└── README.md
```

## 本地预览
直接用浏览器打开 `index.html`，或在目录下运行：
```bash
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 自定义内容
- **基本信息**：编辑 `index.html` 中的 Hero、关于我、技能、作品、联系等区块
- **配色**：修改 `css/style.css` 顶部的 `:root` 变量（`--accent` 等）
- **项目链接**：把作品卡片里的 `href="#"` 换成你的真实链接

## 部署到 GitHub Pages
1. 在仓库 Settings → Pages 中，选择部署来源为 `main` 分支根目录
2. 等待几分钟后访问 `https://<用户名>.github.io/<仓库名>/`
