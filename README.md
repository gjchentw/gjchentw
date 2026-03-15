## 📊 Technical Skills — Past 6 Months

<p align="center">
  <img src="./tech-skills-treemap.svg" alt="Technical Skills Treemap (Sep 2025 – Mar 2026)" width="960"/>
</p>

### 技術占比明細

| 技術 | 占比 | 相關專案 | 說明 |
|:-----|:----:|:---------|:-----|
| **Lean 4 / Mathlib** | 26% | NaturalNumberGame, Monopylean, lean-triangle, lean-pythagorean, mylean | 形式化驗證與數學證明（定理構造、proof workflow、Mathlib 實作）；40 commits |
| **JavaScript / PWA / SQLite WASM** | 24% | mmex-pwa, opfs-cloud-file | PWA 前端工程、OPFS 雲端同步、Web Worker、SQLite WASM、Vite/Jest/npm 發布；56 commits |
| **HTML / Reveal.js** | 13% | slide-sdd-spec-kit | Reveal.js 投影片與 Spec-Driven Development 教學內容製作；30 commits |
| **Java / Gradle (Spigot)** | 11% | Welcome | Minecraft Spigot 外掛開發（i18n、事件驅動快取、JUnit 5 測試、Gradle）；19 commits |
| **Go / Gin** | 9% | go-kittyd | WebSocket 終端伺服器、HTTP 路由、測試與模組化重構；14 commits |
| **Shell / CI-CD (GitHub Actions)** | 7% | mmex-pwa, Welcome, go-kittyd, NaturalNumberGame, slide-sdd-spec-kit | 建置、測試、發布與 GitHub Pages 自動化工作流程設計 |
| **Python / LaTeX Tooling** | 4% | NaturalNumberGame, Monopylean | Lean Blueprint / 文件產線與 LaTeX/數學文檔工具鏈 |
| **Docker / DevContainers** | 3% | Monopylean, compose-php | 容器化開發環境、postCreateCommand 與開發一致性配置 |
| **Markdown / SVG Docs** | 2% | gjchentw | 技術分析文件、README 結構化資訊呈現、SVG 視覺化維護；5 commits |
| **PHP / Nginx** | 1% | compose-php | PHP-FPM + Nginx docker-compose 服務組態與部署範例；4 commits |

> **分析方法**：統計 2025/09/15–2026/03/15 間有活動的 12 個公開 repositories（共 168 commits）。占比採用加權分數：`commit 數 × 專案複雜度係數 × 技術深度係數`，再正規化為 100%。

---

### 📝 可重複使用的 Prompt

<details>
<summary>點擊展開 — 用於產生技術能力 Square Pie Chart 的 Prompt</summary>

```
根據 GitHub 使用者 {USERNAME} 過去 6 個月的公開 GitHub 活動（repositories、commits、使用的程式語言與框架），分析其技術能力組成，並製作一張 SVG 格式的 Square Pie Chart（方形比例圖 / Treemap）。

要求：
1. 查看該使用者過去 6 個月內有活動的所有公開 repositories
2. 分析每個 repo 的主要語言、框架、工具（例如：Go、JavaScript、Docker、Lean 4 等）
3. 根據 commit 數量、專案複雜度與技術深度，計算每項技術的加權占比（百分比）
4. 生成一張精美的 SVG treemap 圖表，其中：
   - 每個方塊的面積與該技術的占比成正比
   - 使用不同顏色區分各項技術
   - 在方塊內標示技術名稱、百分比、相關專案名
   - 包含標題與時間範圍
5. 在 README 中以表格形式詳細列出每項技術的占比、相關專案與說明
6. 將 SVG 檔案放在 repo 根目錄，並在 README 中引用顯示

範例輸出格式：
- SVG 檔名：tech-skills-treemap.svg
- 圖表類型：Squarified Treemap（方形比例圖）
- 參考風格：Our World in Data 的 CO₂ 排放 treemap
```

</details>
