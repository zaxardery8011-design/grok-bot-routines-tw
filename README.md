建排程的教學很多。這裡多教一件事：確認它真的做完。

手機就能用。Grok 手機 App 有你的 Bot，也有「自動化」清單。

## 兩條路，選一條

**第一條。叫你自己的 AI 帶你做。**

1. 把本 repo 的網址丟給你慣用的 AI（ChatGPT、Claude、Gemini 都行）。叫它讀 [AGENTS.md](AGENTS.md)。
2. 它先問你一個答錯會改結果的問題。再幫你填 [短版三格](prompts/短版三格.md) 或 [完整版](prompts/完整版.md)。
3. 你把它給的提示詞，複製貼進你的 Grok Bot 對話。它會回例行名稱和下次執行時間。這一步已驗。

**第二條。直接交給 Grok Bot。**

帳號只有一個 Bot，而且它在跑別的例行時，另開一個 Bot 再丟網址，避免攪亂原本的對話。

1. 把本 repo 的網址丟給你的 Grok Bot。說：「讀這個 repo 的 AGENTS.md，照著幫我建一條例行。」

   新 Bot 會先跳英文選單。直接打字送出即可略過。
2. 它會先問你一題，把填好的提示詞給你看，你說可以它才建。
3. 2026-09-30 和 10-04 兩次實測，那一題都是問產出放哪。形式可能是選擇題或純文字。你沒說要它做什麼，它會先拿範例當題目。
4. 2026-10-04 實測已建立，清單核對通過。2026-10-05 第一次執行交 4 格，4 個連結全部可開。

## 兩條路都要做的最後一步

打開左側欄「自動化」核對那一列。網址是 https://grok.com/automations 。手機 App 也看得到。

AI 說建好了不算數。清單上有那一列才算。

再照 [確認真的做完](verify/確認真的做完.md) 看產出。

## 目錄

- [AGENTS.md](AGENTS.md)。交給你自己的 AI。
- [prompts/短版三格.md](prompts/短版三格.md)。三個空格。
- [prompts/完整版.md](prompts/完整版.md)。照填空底稿。
- [prompts/驗收.md](prompts/驗收.md)。叫它回報上次執行。
- [prompts/修改排程.md](prompts/修改排程.md)。在對話裡改。
- [checks/翻車檢查.md](checks/翻車檢查.md)。常見翻車。
- [verify/確認真的做完.md](verify/確認真的做完.md)。三層確認。
- [examples/每日新聞早報.md](examples/每日新聞早報.md)。
- [examples/挖洞迴圈.md](examples/挖洞迴圈.md)。
- [examples/AI假完工案例蒐集.md](examples/AI假完工案例蒐集.md)。
- [LICENSE](LICENSE)。

## 相關 repo

挖洞迴圈、例行題、檔頭工具在 [dig-loop](https://github.com/zaxardery8011-design/dig-loop)。

本 repo 只連過去。不複製它的腳本。

其他同一家的工具：

- [execution-proofs](https://github.com/zaxardery8011-design/execution-proofs)：AI 說做完就查檔在不在、時間對不對
- [line-persona](https://github.com/zaxardery8011-design/line-persona)：同一套「叫 AI 讀 AGENTS.md」做 LINE 分身
- [minibrain-kit](https://github.com/zaxardery8011-design/minibrain-kit)：這家店怎麼用開源，給學生的 AI 讀

覺得有用，歡迎點星。
