# Android-AI-gateway（镜像备份）

把 Android 手机变成私有的 AI 模型聚合服务器，将 Trae / WorkBuddy / Antigravity / ChatGPT / Loomy 等多家上游账号统一翻译为 OpenAI 兼容端点。

本仓库是 [alarmedvine/Android-AI-gateway](https://github.com/alarmedvine/Android-AI-gateway) 的个人镜像备份：

- **源码**：每天由 [`.github/workflows/sync-upstream.yml`](.github/workflows/sync-upstream.yml) 从上游同步，只增不删，上游删除的文件在本仓库继续保留。
- **安装包**：上游每个 Release 的 APK 资产都会镜像到本仓库对应的 Release，只增不删。
- **下载站**：根目录 `index.html` 从本仓库的 `releases.json` 读取版本信息，所有下载直链指向本仓库，**即使上游仓库被删除，这里的下载链接依然有效**。

## 访问

- 下载站：<https://rdtscx.github.io/Android-AI-gateway/>
- 镜像仓库：<https://github.com/rdtscx/Android-AI-gateway>
- 上游仓库：<https://github.com/alarmedvine/Android-AI-gateway>

## 手动同步

可在 Actions 页面用 `workflow_dispatch` 立即触发一次镜像；定时任务每天 08:00（北京时间）自动执行。

## 许可

跟随上游项目的许可声明，详见上游仓库的 `LICENSE` 与 `THIRD_PARTY-NOTICES.md`。
