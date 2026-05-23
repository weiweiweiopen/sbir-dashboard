# SBIR 1Z1141068 Public Dashboard

公開頁面：<https://weiweiweiopen.github.io/sbir-dashboard/>

這個 repo 放置 SBIR Phase 1 專案的公開行政儀表板與去識別化資料。

## Public data

- `data/public/project.json` — 專案摘要、總預算、公開邊界
- `data/public/budget.csv` — 簽約版預算科目
- `data/public/monthly-plan.csv` — 月度預估支出與實支狀態
- `data/public/actual-expenses.csv` — 可公開的實支流水；目前尚無正式登錄

- `data/public/materials.csv` — 消耗性器材及原材料細項
- `data/public/equipment-use.csv` — 研發設備使用費細項
- `data/public/equipment-maintenance.csv` — 研發設備維護費細項
- `docs/public-transparency.md` — 公開／不公開資料邊界

## Privacy

個人薪資、Simpany 明細、投保資料、銀行帳戶、政府系統截圖與登入憑證不進入 public repo。

## LLM wiki

- `llm-wiki/` — DSSC-PUF strategy, IP landscape, research landscape, defensive firewall, and exported Google Doc baseline.

## Agent / LLM entrypoint

- `llms.txt` — concise machine-readable entrypoint for the public dashboard and LLM wiki.
