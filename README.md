# 成绩本 · Gradebook

一个在浏览器中运行的本地成绩计算器，用于管理多门课程、记录各项成绩并追踪目标分数。界面目前为中文。

## 功能

- 为每门课程添加实验、测验和考试等组成部分，并设置权重和次数。
- 每个部分按各次成绩的平均分，再按权重计入总成绩。
- 设置目标分数，查看进度；使用滑块调整成绩。
- 自动保存在浏览器本地存储，并保留上一份自动备份；支持 JSON 导入与导出。

## 使用

下载项目后，在现代浏览器中打开 `index.html`，无需安装或服务器。直接编辑课程名称，添加组成部分并填写分数。及格线为 50 分。

成绩保存在当前浏览器和本机中，并非保存在项目文件夹内。更换浏览器、清除浏览器数据或换电脑前，请先使用页面上的「导出」功能备份，再通过「导入」恢复。

---

## English

Gradebook is a local browser-based grade calculator for managing multiple courses, recording assessment scores and tracking a target grade. The application interface is currently in Chinese.

### Features

- Add weighted components such as labs, quizzes and exams, each with multiple scores.
- Calculate each component's average and apply its weight to the course total.
- Set a target score and adjust scores with sliders.
- Save data in browser local storage with a previous automatic backup; import and export JSON backups.

### Getting started

Download the project and open `index.html` in a modern browser. No installation or server is required. Edit the course name, add components, set their weights and enter scores. The passing threshold is 50 points.

Your grades are stored in the current browser on your device, not in the project folder. Export a JSON backup before clearing browser data, switching browsers or moving to another computer; use Import to restore it.

