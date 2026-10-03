# TitleGuess 题库

这个公开仓库仅保存经过核验的题库及 GitHub Pages 发布配置。

- 完整题库：`distribution/question-pack.json`，32题，revision 3。
- 历史版本：`distribution/packs/question-pack-v3.json`。
- 版本、字节数与 SHA-256：`distribution/manifest.json`。

首次发布：在 Settings → Pages → Source 选择 GitHub Actions，然后在 Actions 手动运行 **Publish verified question bank**。成功后以 Pages 显示的真实地址为准，题库路径为 `/question-pack.json`。

以后提供资料和来源后，先核验并生成新版 JSON，递增 revision、更新归档及清单，再手动发布。工作流会验证版本、题数、字节数、校验值及版本归档的一致性。
