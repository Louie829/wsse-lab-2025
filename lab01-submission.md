# Lab-01 Submission

## 1. Repo 連結
🔗 https://github.com/Louie829/wsse-lab-2025

## 2. Pull Request 連結（已通過 CI）
🔗 https://github.com/Louie829/wsse-lab-2025/pull/1

## 3. Swagger Editor 截圖
📎 01-editor.png

## 4. PR 綠燈截圖（Checked / Verified）
📎 02-pr-green.png

## 5. CI Log 截圖（swagger-cli validate 成功記錄）
📎 03-actions-log.png

---

## 6. 重點片段連結（檔案行號連結即可）
📄 `openapi/openapi.yaml`  
🔗 https://github.com/Louie829/wsse-lab-2025/blob/main/openapi/openapi.yaml

- `/health`  
- `GET /students`  
- `POST /students`（含 `201 + Location`）  
- `Student` 與 `Error` 兩個 schema  

以上內容均可於上方 openapi.yaml 檔案中檢視。

---

## 7. 備註
- 已建立 `.github/workflows/openapi-ci.yml`  
- 在 Pull Request 建立時自動執行 swagger-cli validate  
- CI 驗證成功並顯示通過記錄 ✔
