# 火蛙科技官网

火蛙科技是一家专注于智能家居软硬件开发的科技公司，致力于为现代家庭提供智能化、便捷化的生活体验。

## 网站特色

- 🏠 **智能家居解决方案** - 提供完整的智能家居软硬件解决方案
- ⚡ **高效节能** - 采用先进的节能技术，环保智能
- 🔧 **定制开发** - 根据客户需求提供个性化定制服务
- 🛡️ **安全可靠** - 严格的安全标准和质量控制

## 技术栈

- **Jekyll** - 静态网站生成器
- **GitHub Pages** - 网站托管
- **HTML5/CSS3** - 现代化响应式设计
- **JavaScript** - 交互功能

## 本地开发

### 环境要求

- Ruby 2.7 或更高版本
- Bundler

### 安装步骤

1. 克隆仓库
```bash
git clone https://github.com/averyhome/averyhome.github.io.git
cd averyhome.github.io
```

2. 安装依赖
```bash
bundle install
```

3. 启动本地服务器
```bash
bundle exec jekyll serve
```

4. 访问网站
打开浏览器访问 `http://localhost:4000`

## 项目结构

```
├── _config.yml          # Jekyll配置文件
├── _layouts/            # 布局模板
│   └── default.html     # 默认布局
├── _data/               # 数据文件
│   └── navigation.yml   # 导航配置
├── assets/              # 静态资源
│   └── css/
│       └── style.css    # 样式文件
├── index.md             # 首页
├── about.md             # 关于我们
├── products.md          # 产品中心
├── contact.md           # 联系我们
└── README.md            # 项目说明
```

## 部署

网站已配置为使用GitHub Pages自动部署。每次推送到主分支时，GitHub Pages会自动构建并部署网站。

## 联系方式

- **邮箱**: contact@firefrog.tech
- **电话**: 400-888-8888
- **地址**: 北京市海淀区中关村科技园创新大厦A座1001室

## 许可证

© 2024 火蛙科技. 保留所有权利.
