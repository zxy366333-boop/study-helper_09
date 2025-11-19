# study-helper_09
**项目名**：study-helper_09
**作者**：张欣雨
**学号后两位**：09

## 项目简介
`study-helper_09` 是一个极简的前端单页应用（学习小助手），用于记录学习任务 / 学习笔记，演示开源协作流程（分支、PR、issue、license、文档等）。代码采用纯 HTML/CSS/JavaScript，无需后端，可部署到 GitHub Pages。

## 功能（最小可行）
* 添加任务（文本）
* 标记任务为完成 / 取消完成
* 删除任务
* 可导出为 JSON（或复制到剪贴板）
* 简单离线本地存储（localStorage）

## 运行方式
1. 直接打开 `index.html`（无需构建）
2. 或部署到 GitHub Pages：Settings → Pages → 选择 main 分支 root

## 项目结构
```
index.html
css/style.css
js/app.js
README.md
LICENSE
CONTRIBUTING.md
.github/ISSUE_TEMPLATE.md
.github/PULL_REQUEST_TEMPLATE.md
docs/design.md
```

## 开发与分支策略
* `main`：稳定发布分支（用于 GitHub Pages）
* `dev`：开发集成分支
* `feature/*`：功能分支（例如 `feature/add-todo`）

贡献流程（简要）：
1. 新建 feature 分支：`git checkout -b feature/xxx`
2. 提交并 push：`git push origin feature/xxx`
3. 在 GitHub 发起 PR，至少一个 reviewer 批准后合并。

## 如何参与（欢迎同学参与）
* 提交 issue：功能建议 / Bug 报告 / 文档修改
* 发起 PR：任何小改动都欢迎（例如改进样式、增加国际化文案）
* 给仓库 star、watch 来支持项目

## 文件模板（仓库内）
* `.github/ISSUE_TEMPLATE.md`：Issue 模板
* `.github/PULL_REQUEST_TEMPLATE.md`：PR 模板
* `CONTRIBUTING.md`：贡献指南

## License
本项目使用 **MIT License**（放在仓库根目录的 LICENSE 文件中）。

## 五看三定（项目分析）
**五看**：
* 行业/趋势：教育类轻量工具受学生欢迎，利于课堂演示。
* 市场/客户：目标是大学生与自学者，需求为快、轻、易分享。
* 竞争：与大型产品（如 Notion、Todoist）不同，定位为教学 demo 与开源协作展示。
* 自己（能力）：纯前端实现成本低，便于在有限时间内完成。
* 机会：通过 GitHub Pages 分享、课堂推广，可吸引同学参与 issue/PR。

**三定**：
* 定战略控制点：保证项目易复现、易参与（文档齐全、模板完善）。
* 定目标：
  * 实现基本功能并部署（技术目标）。
  * 至少 3 个 issue、1 个 PR、5+ star（参与目标）。
  * 文档齐全（文档目标）。
* 定策略：采用 `dev`+`feature/*` 分支，PR 必须有 review；课堂内主动分享并引导参与。

## 联系 & 致谢
如果你是本课程同学，请在仓库中提交 issue 或发 PR。谢谢你的参与！



（可在 README 中补上演示截图与 GitHub Pages 链接）
# study-helper_09
