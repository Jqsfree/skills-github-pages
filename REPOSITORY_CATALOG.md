# 学习示例目录

本仓库集中保留 GitHub 学习材料和练习。原 GitHub Pages 课程文件与网站地址保持不变。

- **GitHub Pages / Jekyll**：根目录 README 和 `.github/steps/`。
- **Codespaces / Node.js 示例**：`examples/codespaces-haikus/`，来源 `laughing-octo-eureka`；从该目录按原 package.json 使用 npm 命令。
- **GitHub Flow / C 语言练习**：`examples/hello-world/`，来源 `hekko-world`；代码入口 `hello.c`。

各子目录保留原文件、LICENSE（如源仓库有）和 Git 历史。子目录内 `.github/workflows/` 仅作为练习资料，不会自动成为根仓库工作流。
旧源 README 内仓库地址属于历史记录，新的代码入口以上述路径为准。

`hekko-world` 的两个历史 PR 讨论、评审、提交清单与补丁保存在 `.repository-history/hekko-world/`。
这些是历史快照，不能恢复为本仓库原生 PR，但原始提交仍通过 `imported/hekko-world/*` 标签可访问。
每个来源全部 Git refs 均保留为 `imported/<源仓库>/<原引用路径>` 标签；完整映射见 `.repository-history/final-organization.json`。

本仓库完成整理后继续保持原有归档状态，既有网站仍在原地址；课程自动化没有为本次迁移重新执行。
