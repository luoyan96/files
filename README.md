# AcceptCat 团队资料示例

本仓库为 **公开示例空间**，用于验证 AcceptCat 团队资料工作区。全部内容是可公开的合成示例，没有真实实验、专利或项目结论。

## 首次配置

- 仓库：`https://github.com/luoyan96/files.git`
- 发布分支：`main`
- 资料空间 ID：`acceptcat-demo`
- 目录：`acceptcat-library.json`，每个条目声明稳定 ID、项目、用途、相对路径及 SHA256。

## 维护方式

小型 Markdown、目录和项目要求随 Git 管理。PPT / PDF 等原件优先通过 AcceptCat 现有共享原件服务保存，目录只登记 `shared` 引用（fileId、version、sha256）。本地指针用 `local`，不会自动把文件传给其他成员。

客户端提交更新到独立分支；在 GitHub 创建 PR、审核合并后，成员再同步发布分支。不得把“分支提交成功”说成“团队已发布”。客户端首次运行需要 Git for Windows 及本机已有的仓库访问权限。

公开仓库的文件、文件名、说明和历史均公开可见。请勿加入实验室内部原件、密钥、私人数据或未经授权的材料。

## 迁移

后续可以转移到实验室 GitHub 仓库或推送完整历史后修改 AcceptCat 仓库配置。保留 workspaceId、projectId、entryId 和相对路径，避免把旧任务来源误认为另一份材料。共享原件仍需维持原权限和可访问性；仅搬 Git 不会复制原件服务或自动授权。
