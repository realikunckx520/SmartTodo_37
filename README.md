📘 SmartTodo_37
一、项目简介

SmartTodo 是一个基于 前后端分离 思想实现的迷你任务管理系统。前端采用 HTML + 原生 JS，后端采用 Python Flask 简易接口。
项目用于展示 GitHub 规范化流程，包括：

分支管理

Pull Request

冲突解决

issue 协作

README、项目文档、LICENSE

用“五看三定”进行项目战略分析（docs/strategy_five_see_three_set.md）

本仓库用于完成 “期末课程考查项目”。

二、项目功能（简易版）

添加待办事项

删除待办事项

前后端分离交互（本地可运行）

用 Python 模拟 RESTful API

三、技术栈
模块	技术
前端	HTML、CSS、JavaScript（原生）
后端	Python Flask
文档	Markdown
版本控制	Git & GitHub
四、项目结构
src/
 ├── index.html       # 前端界面
 └── api_server.py    # 后端 API

docs/
 ├── project_overview.md
 ├── branch_management.md
 └── strategy_five_see_three_set.md

五、如何运行
▶ 启动后端（需要 Python）
cd src
pip install flask
python api_server.py


后端默认运行在：

http://localhost:5000

▶ 打开前端

双击：

src/index.html


即可使用。

六、分支说明（详细见 docs/branch_management.md）

main —— 主分支

feature-ui —— 前端开发

feature-api —— 后端开发

bugfix-conflict-demo —— 冲突演示

七、许可证

本项目采用 MIT License。

八、贡献方式（用于课程考核）

欢迎同学提出 Issue：

BUG 反馈

新功能建议

Star ⭐ / Watch 👁 支持
