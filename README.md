# 溝通處世顧問（gentle-boundaries）

> 受蔡康永公開訪談、媒體訪問，以及《奇葩說》節目中他分享的故事與觀點啟發的獨立研究版。

這是一個處理「難開口、難回、難拒絕」的溝通 Skill。它會先問清楚你的處境與底線，再幫你寫出溫和、明確、不留錯誤期待的回覆。

它不做真人口吻模仿，也不假裝是蔡康永本人。公開版保留可執行的能力：

1. **體面婉拒**
2. **棘手客服／合作窗口回信**
3. **學員或他人故事陪伴**

## 適用情境

- 婉拒合作邀約、演講、會議或社交活動
- 拒絕免費加做、超出合約的修改與不合理時程
- 客服情緒上來、反覆追問、需要先穩住人再守範圍
- 學員／讀者分享真實故事後，你內心有感卻不知怎麼回
- 想保留關係，但不想用模糊語氣讓對方繼續等待

## 安裝方式

GitHub repo：[gentle-boundaries-skill](https://github.com/Raymondhou0917/gentle-boundaries-skill)

> 課程上線前 repo 維持 private；上線後改 public，既有安裝指令與連結即可生效。

```bash
npx skills add Raymondhou0917/gentle-boundaries-skill
```

你也可以把整個資料夾複製到 AI Agent 的 skills 目錄。安裝後，把範例和觸發詞換成你最常遇到的情境。

## 檔案結構

```text
/
├── SKILL.md
├── README.md
├── LICENSE
├── THIRD_PARTY_NOTICES.md
└── references/
    ├── communication-workflow.md
    ├── refusal-mode.md
    ├── difficult-reply-mode.md
    ├── companion-mode.md
    ├── expression-dna.md
    ├── examples.md
    └── public-source-notes.md
```

## 研究方式

本公開版研究蔡康永的公開訪談截取、公開媒體訪問，以及《奇葩說》中他分享的相關故事與觀點，蒸餾成可運行的溝通框架與風格化表達 DNA。研究過程只保存自行整理的摘要、工作流與測試案例，不收錄逐字語料庫，也不要求 AI 重現特定句子。

主要觀察：

- 先接住人，再處理事情與邊界
- 在乎對方感受，但不為討好而失去自己
- 決定要說清楚；替代方案必須做得到
- 陪伴可以整理選項，不代替人生重大決定
- 真實的人會有停頓與不完美，不需要用口頭禪製造「像本人」

可核對的公開來源與研究摘要見 [`references/public-source-notes.md`](./references/public-source-notes.md)。

## 獨立研究與授權聲明

- 本專案未獲蔡康永本人、經紀公司或任何權利人授權、合作或背書。
- 「蔡康永」姓名只用於說明研究靈感與課程案例，不代表本人參與本 Skill。
- MIT License 只涵蓋本專案自行撰寫的工作流、提示詞、範例與程式。
- 第三方姓名、肖像、訪談、節目、影片及其內容不在 MIT License 授權範圍內。

完整說明見 [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md)。
