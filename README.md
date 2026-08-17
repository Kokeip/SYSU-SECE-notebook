# SYSU-SECE-notebook
## 个人总结的中山大学电子与通信工程学院期末复习笔记
遗憾暂时只找到这些笔记，希望学弟学妹们可以提PR补充。

## 如何贡献

欢迎补充、修订和整理电子与通信工程学院课程的复习资料。提交前请确保内容来源可靠，注意保护个人隐私，并避免上传受版权保护且不适合公开传播的材料。

建议每个 PR 聚焦一项改动，例如新增一门课程的笔记、修正一处错误，或优化现有资料的目录与说明。文件名请尽量清晰，便于按课程和内容查找。

### 提交 PR 的步骤

1. 在 GitHub 上打开本仓库，点击右上角的 **Fork**，将仓库复制到自己的账号下。
2. 克隆自己的 Fork，并进入项目目录：

   ```bash
   git clone https://github.com/<你的用户名>/SYSU-SECE-notebook.git
   cd SYSU-SECE-notebook
   ```

3. 从默认分支新建一个描述清楚的分支：

   ```bash
   git checkout -b add-<课程名>-notes
   ```

4. 添加或修改资料。请检查文件是否放在合适的课程目录中，确认内容可以公开分享，并避免一次提交混入无关改动。
5. 查看改动并提交：

   ```bash
   git status
   git add <文件或目录>
   git commit -m "docs: 补充<课程名>复习笔记"
   ```

6. 推送分支到自己的 Fork：

   ```bash
   git push origin add-<课程名>-notes
   ```

7. 回到 GitHub 上自己的 Fork，点击 **Compare & pull request**，将目标仓库设为 `Kokeip/SYSU-SECE-notebook`，目标分支设为默认分支。
8. 在 PR 描述中简要说明：补充或修改了什么、资料适用的课程/学期，以及是否有需要维护者特别注意的地方。确认无误后提交 PR，随后根据评论补充或调整即可。

如果你不熟悉 Git，也可以直接在 GitHub 网页中进入对应目录，点击 **Add file → Upload files** 上传资料，然后选择 **Create a new branch for this commit and start a pull request**。
