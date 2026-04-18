# 🛡️ Hefei University AI Safety Lab | 合肥大学安全人工智能团队主页

欢迎来到合肥大学安全人工智能团队官方网站的代码仓库。本项目是一个纯静态的响应式网页，旨在展示实验室的**最新动态、学术成果、团队成员及开源资料**。

网站采用极致轻量化的架构，无需复杂的编译打包过程，修改代码后保存即可实时预览，非常适合学术团队的快速迭代与日常维护。

---

## 🛠️ 技术栈 (Tech Stack)

- **核心结构**：HTML5 + CSS3 + 原生 JavaScript
- **UI 框架**：[Bootstrap 5.3.0](https://getbootstrap.com/) (负责响应式网格布局和现代组件)
- **图标库**：[FontAwesome 6.4.0](https://fontawesome.com/) (用于展示邮箱、定位、PDF、DOI等精美图标)
- **访问量统计**：[不蒜子 (Busuanzi)](http://ibruce.info/2015/04/04/busuanzi/) (纯前端极简页面浏览量/访客统计)

---

## 📂 目录结构 (Directory Structure)

```text
📁 AI-Safety-Lab-Website
├── 📄 index.html              # 网站主页（包含实验室简介、最新动态、研究方向、学术成果、页脚联系方式）
├── 📄 team.html               # 团队概览页（展示指导教师信息及各年级学生入口）
├── 📄 students_2023.html      # 2023级研究生详情列表
├── 📄 students_2024.html      # 2024级研究生详情列表
├── 📄 students_2025.html      # 2025级研究生详情列表
├── 📄 downloads.html          # 资料下载页（开源代码合集、论文网盘链接、课程视频资料）
└── 📁 assets                  # 静态资源文件夹
    ├── 📁 images              # 图片资源（新闻配图、网络架构图如 1.png/2.png，以及学生照片 stu_xxx.jpg）
    └── 📁 papers              # 本地文献资料（存放在本站的 PDF 文件，如 GraphLoRA.pdf 等）
