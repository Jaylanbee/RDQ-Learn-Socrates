# RDQ-Learn-Socrates — 蘇格拉底式課後複習四象限法（OpenCode 版）

**Socratic Learning Review Quadrant Method**
一個給 [OpenCode](https://opencode.ai) 用的課後複習 Skill。

> 我不給你答案，我用問題讓你發現你已經會的，以及你還不知道你不知道的。

---

## 這是什麼

RDQ-Learn-Socrates 把四象限架構移植到**學習覆盤**場景，並以**蘇格拉底式對話**貫穿全程：

| 象限 | 意義 | 蘇式做法 |
|---|---|---|
| **Ⅰ** | 已經記住的內容 | 用問的引導回憶，不幫他條列 |
| **Ⅱ** | 知道自己不會的地方 | 用反問引導他自行推導，不給答案 |
| **Ⅲ** | 學了卻沒發現自己會了 | 連鎖追問讓他發現隱性知識 |
| **Ⅳ** | 完全沒想過的關聯知識 | 提示性問題讓他自己意識到盲區 |

核心原則：**不給答案，只問問題。**

---

## 安裝

```powershell
git clone https://github.com/Jaylanbee/RDQ-Learn-Socrates.git $env:USERPROFILE\.config\opencode\skills\rdq
```

裝好後重開 OpenCode。

---

## 使用

講人話：「**用 RDQ 複習 OOO**」

### 你會經歷什麼
1. **蘇式引導回憶** — 我不列你學了什麼，我問你腦子裡最先浮出來的是什麼
2. **你的問題你來答** — 你問「為什麼」，我問「你覺得最像哪個你已經知道的？」
3. **隱性知識挖掘** — 我追問 2–3 層，讓你發現自己其實已經會了什麼
4. **盲區提示** — 我用一個問題讓你自己發現「原來還有這個方向」
5. **學習覆盤卡** — 記錄你經過追問浮現的關鍵發現
6. **你確認** — 掃一眼說可以，完成

Lite 模式全程只打擾你 **2 次**。

---

## 檔案結構

```
rdq/
├── SKILL.md
└── references/
    ├── question-bank.md
    └── spec-template.md
```

---

## 授權

MIT License
