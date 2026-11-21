# CS50P × PyTorch · 双语学习打卡 / Bilingual Study Check-in

哈佛 CS50P《Python 编程入门》知识点整理（面向 PyTorch 神经网络方向），做成单文件网页应用。

Harvard CS50P (Introduction to Programming with Python) knowledge notes, oriented toward PyTorch, packaged as a single-file web app.

**在线使用 / Live**: https://mazh114.github.io/cs50p-pytorch-notes/

## 功能 Features

- **侧边栏目录**：按讲次排列，点击直达对应章节；顶部 ☰ 按钮可收起/展开。
  Sidebar TOC with one-click navigation; collapsible via the ☰ button.
- **多用户进度**：输入名字即可创建自己的档案，打卡数据按用户分开保存在浏览器 localStorage；支持切换用户、导出/导入 JSON 备份。
  Per-user progress stored in localStorage; switch users anytime; export/import JSON backups.
- **打卡系统**：每讲一个大打卡栏，每个知识点、每道习题各有小打卡栏，打卡自动记录日期；侧边栏和每讲头部显示实时进度条。
  A big check-in per chapter, a small check-in per knowledge point and per exercise, each stamped with its date; live progress bars in the sidebar and chapter headers.

## 说明 / Note

打卡数据保存在本地浏览器（localStorage），换设备或清缓存会丢失，请用「导出备份」保存。
Check-in data lives in the browser's localStorage — export a backup before switching devices or clearing cache.

## 内容来源 / Sources

- 课程 / course: [CS50P 官方讲义](https://cs50.harvard.edu/python/) · [freeCodeCamp 全课程视频](https://www.youtube.com/watch?v=nLRL_NcnK-4)
- 本地完整笔记 / full local notes: `cs50p_notes.md`、`cs50p_exercises_answers.md`（在本仓库外的本地学习文件夹中）
