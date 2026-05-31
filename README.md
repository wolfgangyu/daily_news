# 📡 每日新聞速遞

由 [Horizon](https://github.com/Thysrael/Horizon) AI 自動產生的每日新聞摘要，使用[繁體中文版 fork](https://github.com/wolfgangyu/Horizon-zh-tw) 建置。

🌐 **線上閱讀**：[www.519275.xyz](https://www.519275.xyz/)

## 關於

此網站每天早上 7:30（台灣時間）自動更新，AI 從多個來源蒐集新聞，經過評分、去重、補充背景知識後，產生結構化的繁體中文摘要。

涵蓋主題：**AI 科技**、**台灣時事**、**國際政治**、**體育**、**知識管理**。

### 新聞來源

- **Hacker News** — 科技與綜合社群熱門文章
- **Reddit** — r/MachineLearning、r/artificial、r/ClaudeAI、r/taiwan、r/PKMS
- **RSS** — Simon Willison、OpenAI、iThome、NHK、NYT、WSJ、中央社
- **Twitter/X** — @elonmusk、@karpathy、@ChingteLai、@iingwen 等
- **GitHub** — torvalds、claude-code、ollama、uv 等專案動態
- **Threads** — 賴清德、蔡英文等（透過自架 RSSHub）
- **OSS Insight** — GitHub 每日趨勢專案

### 技術架構

- **AI 模型**：[Ollama](https://ollama.com/) 本地模型（gemma4:e4b），無需付費 API
- **執行方式**：Docker Compose，每日 cron 排程
- **RSS 擴充**：自架 [RSSHub](https://github.com/DIYgod/RSSHub) 提供 Threads 等來源
- **發佈方式**：自動推送至此 repo，由 Jekyll + GitHub Pages 建置

## 相關連結

- [Horizon 繁體中文版](https://github.com/wolfgangyu/Horizon-zh-tw) — 本站使用的 Horizon fork
- [Horizon 原版](https://github.com/Thysrael/Horizon) — 上游專案

## 授權

內容由 AI 自動產生，新聞來源版權屬於各原始出處。Horizon 專案採用 [MIT 授權](https://github.com/Thysrael/Horizon/blob/main/LICENSE)。
