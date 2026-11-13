# 羅謝逸｜實務與研究之間

霧香配色的 10 分鐘報告網站。保留七個報告畫面、逐頁模式、倒數計時與四步驟互動示範。

## 發布至 GitHub Pages

1. 建立儲存庫，例如 `luo-research-report`。
2. 將本資料夾內的檔案放到儲存庫根目錄；不要只上傳 ZIP。
3. 在儲存庫 Settings → Pages → Build and deployment，選擇 Deploy from a branch。
4. 選 main 分支與 /(root)，儲存。
5. 等待發布完成，使用 Pages 頁面實際顯示的網站網址。

一般 GitHub Pages 網站可公開瀏覽，並不沿用原網站的私人權限。請在啟用前確認履歷及專案資訊適合公開。

## 自己修改內容

在 GitHub 打開 index.html，按編輯按鈕，搜尋以下 section id，修改標籤之間的文字，再 Commit changes。請保留 HTML 標籤、id 及 class。設定 Pages 後，提交到發布分支即可觸發更新。

| 區塊 id | 內容 |
|---|---|
| intro | 封面標題、姓名與學校 |
| about | 自我介紹與能力 |
| practice | 實務案例與成果 |
| research | 論文題目、研究問題 |
| progress | 論文進展與下一步 |
| skills | 技能分享標題與步驟名稱 |
| closing | 收尾內容 |

互動步驟的詳細說明在 script.js 的 content 陣列。修改第一步時，也同步修改 index.html 中 demo 區塊的預設文字。
配色在 styles.css 開頭的 :root 變數。--bg 是背景，--ink 是主要文字，--purple 是霧紫，--sage 是灰綠。

## 本機預覽

直接以瀏覽器開啟 index.html。此網站沒有外部套件、後端、帳密或建置需求。
若要改頁數，須同步調整 script.js 中頁數及導覽上限。
論文待確認資訊保留原有標示，請依實際進展自行更新。

## 官方文件

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
