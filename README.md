# My First Vibe Coding

## 開發環境

本專案使用 Docker Dev Container 建立開發環境，程式碼來源參考自 [Claude Code 官方 GitHub](https://github.com/anthropics/claude-code) 提供的 Dev Container 範本。

基於官方範本，我做了以下調整：

- **時區設定**：將預設時區改為 `Asia/Taipei`（見 `devcontainer.json` 中的 `TZ` 參數）
- **Container 名稱**：將 `--name` 改為 `first_vibe_coding`（見 `devcontainer.json` 中的 `runArgs`）

> 如果你要 fork 或使用本專案，請記得到 `.devcontainer/devcontainer.json` 中修改 container 名稱（`--name`）和時區，以符合你自己的需求。

## 截圖

![screenshot](2026-02-09%2023.24.51.png)
