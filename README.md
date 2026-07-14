---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 6ef33f045255566dbe251905d450323f_820881347f3911f18ce5525400826444
    ReservedCode1: 1iZqUHwEVL3j3TZ+zg8Gw8cg8nTHf9mcMfGi9+M0S0uW8qmfsTm6NkOfVQeQKWCGf2HEdc9eNj1VHHGXIkjRKu+KK9rVns8IGGkNYWeJL+eMdO6t4ee8KvC7j0sQoDFwN1Ft5/5f2WUXwT5tYmjrWF2iBXgaJUyW2LhosDP6mlH05OZlRLV5+W2seW0=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 6ef33f045255566dbe251905d450323f_820881347f3911f18ce5525400826444
    ReservedCode2: 1iZqUHwEVL3j3TZ+zg8Gw8cg8nTHf9mcMfGi9+M0S0uW8qmfsTm6NkOfVQeQKWCGf2HEdc9eNj1VHHGXIkjRKu+KK9rVns8IGGkNYWeJL+eMdO6t4ee8KvC7j0sQoDFwN1Ft5/5f2WUXwT5tYmjrWF2iBXgaJUyW2LhosDP6mlH05OZlRLV5+W2seW0=
---

# 赵良度 · 个人网站

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://zhaoliangdu.github.io/)

高级Java开发工程师个人网站，基于 HTML5 UP "Read Only" 模板构建。展示专业技能、项目经验与联系方式。

## 技术栈

- **后端**：Java · SpringBoot · SpringCloud · MyBatis · MySQL · PostgreSQL · Oracle · Redis · RabbitMQ
- **前端**：Vue · React · 微信小程序 · HTML5 · CSS3
- **AI**：AI API 集成 · 智能体开发 · Skill 开发 · AI 辅助全流程研发
- **工程化**：Git · Maven · Jenkins · Linux 部署 · Nacos · Sentinel

## 本地运行

```bash
git clone https://github.com/zhaoliangdu/zhaoliangdu.github.io.git
cd zhaoliangdu.github.io
# 直接用浏览器打开 index.html，或使用任意静态服务器
python -m http.server 8000
```

访问 `http://localhost:8000` 即可预览。

## 项目结构

```
.
├── index.html          # 主页面
├── _config.yml         # Jekyll 配置
├── images/             # 图片资源（头像、横幅、项目截图）
│   ├── avatar.jpeg
│   ├── banner.jpg
│   └── ...
└── assets/             # 静态资源
    ├── css/            # 样式
    ├── js/             # 脚本
    ├── sass/           # SCSS 源文件
    └── webfonts/       # Font Awesome 字体
```

## 部署

本站通过 GitHub Pages 自动部署，推送至 `main` 分支即可触发构建。

> **注意**：`_config.yml` 中已移除 Jekyll 默认主题配置（`theme: jekyll-theme-cayman`），确保自定义 HTML 模板正常渲染。

## 待完善

- [ ] 替换项目截图（`images/pic01.jpg` ~ `pic03.jpg`）为真实项目截图
- [ ] 在 [Formspree](https://formspree.io/) 注册并替换联系表单的 `your-form-id`
- [ ] 替换邮箱为真实联系方式
- [ ] 添加 `images/favicon.ico` 网站图标

## License

Design: [HTML5 UP](https://html5up.net) (CCA 3.0) | Content: &copy; 2025 赵良度
*（内容由AI生成，仅供参考）*
