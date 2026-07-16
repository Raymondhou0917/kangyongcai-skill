# 體面拒絕顧問

> 受蔡康永公開言論、採訪與影片內容啟發的獨立研究版。

這是一個專門處理「難拒絕」的輕量 Skill。它會先問清楚你的處境與底線，再幫你寫出一段溫和、明確、不留錯誤期待的回覆。

它不做真人口吻模仿，也不假裝是蔡康永本人。公開版只保留一個可執行的能力：**教人如何溫和但堅定地拒絕。**

## 適用情境

- 婉拒合作邀約、演講、會議或社交活動。
- 拒絕免費加做、超出合約的修改與不合理時程。
- 面對折扣、借錢、幫忙、插隊等難開口的要求。
- 想保留關係，但不想用模糊語氣讓對方繼續等待。

## 安裝方式

公開 repo：[gentle-boundaries-skill](https://github.com/Raymondhou0917/gentle-boundaries-skill)。

```bash
npx skills add Raymondhou0917/gentle-boundaries-skill
```

你也可以把課程內整個 `tsai-kangyong-eq/` 資料夾複製到 AI Agent 的 skills 目錄。安裝後，可以把範例和觸發詞換成你最常遇到的情境。

這份 Skill 刻意維持輕量。你的客戶關係、工作習慣與底線，才是之後最值得加入的內容。

## 檔案結構

```text
/
├── SKILL.md
├── README.md
├── LICENSE
├── THIRD_PARTY_NOTICES.md
└── references/
    ├── refusal-workflow.md
    ├── examples.md
    └── public-source-notes.md
```

## 研究方式

本公開版研究蔡康永的公開言論、採訪與影片內容，蒸餾成可運行的拒絕框架。研究過程只保存自行整理的摘要、工作流與測試案例，不收錄逐字語料庫，也不要求 AI 重現特定句子。

主要觀察：

- 拒絕是可以練習的日常能力。
- 表達前先弄清楚自己願意承擔什麼。
- 語氣可以照顧對方，決定仍要說清楚。
- 真實的人會有停頓與不完美，不需要用大量口頭禪製造「像本人」的效果。

可核對的公開來源與研究摘要見 [`references/public-source-notes.md`](./references/public-source-notes.md)。

## 獨立研究與授權聲明

- 本專案未獲蔡康永本人、經紀公司或任何權利人授權、合作或背書。
- 「蔡康永」姓名只用於說明研究靈感與課程案例，不代表本人參與本 Skill。
- MIT License 只涵蓋本專案自行撰寫的工作流、提示詞、範例與程式。
- 第三方姓名、肖像、訪談、影片及其內容不在 MIT License 授權範圍內。

完整說明見 [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md)。
