# 金融市场基础知识 · 练习 App 📚

一个基于 2026 证券从业资格考试《金融市场基础知识》精讲班重点整理的**纯前端在线练习 App**。无需安装、无需后端，打开浏览器即可使用。

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## ✨ 功能特色

- 📝 **60+ 精选题目** — 覆盖金融市场体系、中国金融体系、证券市场主体、股票四大章节
- 🎯 **三种题型** — 单选题、多选题、判断题
- 🔍 **灵活筛选** — 按章节或按题型定向刷题
- 🔀 **顺序/随机切换** — 支持顺序学习或随机抽题
- ✅ **即时反馈** — 提交后自动判分、高亮正确/错误答案，并展示解析
- 📊 **实时统计** — 显示进度、正确率、最终得分与评语
- 📱 **响应式设计** — 手机、平板、电脑均可完美使用
- 🚀 **零依赖** — 纯 HTML + CSS + JS 单文件，离线可用

---

## 🎬 快速开始

👉 **在线体验：https://ZW471.github.io/securities-exam-practice/**

---

## 📖 使用说明

1. **选择章节** — 顶部下拉框选择"全部章节"或具体章节
2. **选择题型** — 可筛选单选、多选或判断题
3. **点击「开始/重置」** — 生成题目列表
4. **答题**
   - 单选题：点击选项直接选中
   - 多选题：可点击多个选项后再提交
   - 判断题：二选一
5. **提交答案** — 查看对错与解析
6. **上一题 / 下一题** — 自由导航
7. **完成全部题目** — 查看最终得分与评语
8. **随机模式** — 点击「🔀 顺序/随机」切换出题顺序

---

## 📂 文件结构

```
securities-exam-practice/
├── index.html      # 练习 App 主文件（HTML + CSS + JS 全内嵌）
└── README.md       # 说明文档
```

---

## 🗂️ 题库范围

| 章节 | 内容 | 难度 |
|------|------|------|
| 第一章 | 金融市场体系（金融市场概述、国际金融市场） | ⭐⭐ |
| 第二章 | 中国金融体系与多层次资本市场 | ⭐⭐⭐⭐ |
| 第三章 | 证券市场主体（发行人、投资者、中介机构等） | ⭐⭐⭐ |
| 第四章 | 股票（概述、发行、交易、估值） | ⭐⭐⭐ |

题目来源于互联网公开资料，由 Claude Code 整理编排。

---

## 🛠️ 自定义扩展

想添加更多题目？直接编辑 `index.html` 中的 `questionBank` 数组：

```javascript
{
  ch: 1,              // 章节编号 (1-4)
  type: 'single',     // 题型: 'single' | 'multi' | 'tf'
  q: '题目内容',
  opts: ['选项A', '选项B', '选项C', '选项D'],
  ans: [0],           // 正确答案索引数组（多选可有多个）
  exp: '解析说明'
}
```

若要新增章节，同时在 HTML 的 `<select id="chapterSelect">` 中添加对应 `<option>` 即可。

---

## 🎨 技术栈

- **HTML5** — 结构
- **CSS3** — 渐变、响应式布局、动画
- **原生 JavaScript (ES6+)** — 状态管理、DOM 渲染
- **无任何第三方依赖** — 纯静态文件即可运行

---

## 📝 部署到 GitHub Pages

1. 仓库 → `Settings` → `Pages`
2. `Source` 选择 `Deploy from a branch`
3. `Branch` 选择 `main` / `(root)`
4. 保存后几秒钟即可通过 `https://ZW471.github.io/securities-exam-practice/` 访问

---

## ⚠️ 免责声明

- 本项目仅供个人学习、备考之用
- 题目来源于互联网公开资料，由 Claude Code 整理编排
- 本项目**不能替代**官方教材与真题训练，请配合官方资料使用

---

## 🤝 贡献

欢迎提交 Issue 或 PR 补充题目、修正错误：

1. Fork 本仓库
2. 创建分支：`git checkout -b feature/add-questions`
3. 提交修改：`git commit -m 'Add questions for chapter 5'`
4. Push：`git push origin feature/add-questions`
5. 发起 Pull Request

---

## 📜 License

本项目代码采用 [MIT License](LICENSE) 开源；题目内容仅用于学习交流。

---

## ⭐ 如果这个项目对你的备考有帮助，欢迎 Star！

祝大家早日通过证券从业资格考试 🎉
