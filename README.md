# SuSuAI™ 公開介紹站

這個 repository 只包含 **SuSuAI 台灣民事訴訟書狀自動化工具**的 GitHub Pages 公開品牌與文件網站。網站介紹產品功能、工作流程、資料安全與系統分工；真正的案件對話、附件處理、AI 辨識、資料保存與文件產出，均在 [SuSuAI 正式站](https://susuai2.manus.space/)登入後進行。

> 本公開網站不提供登入、表單、檔案上傳、案件處理或資料庫功能，也不接收或保存案件資料。AI 輔助內容不構成正式法律意見，法律文件仍應由承辦律師核閱。

| 項目 | 說明 |
|---|---|
| 公開網站 | <https://kuohuafan.github.io/susuai-pages/> |
| 正式應用 | <https://susuai2.manus.space/> |
| 技術形式 | 原生 HTML、CSS、JavaScript |
| 發布方式 | GitHub Pages，來源為 `main` 分支根目錄 |
| 公開資料 | 產品介紹、流程、安全原則、FAQ |
| 不公開資料 | 全端原始碼、資料庫 schema、migration、密鑰、案件資料、內部文件 |

## 本機預覽

本網站不需要建置。可以使用任一靜態 HTTP server 在 repository 根目錄預覽；不要用 `file://` 作為正式發布驗收，因為它不能完整模擬 HTTP 路徑與快取行為。

## 維護原則

所有「開始使用」「登入」與「進入工作台」連結都必須導向 `https://susuai2.manus.space/`。新增檔案前應確認不含案件、帳號、秘密、資料庫連線或私人分享 token。更新 canonical URL、`robots.txt` 或 `sitemap.xml` 時，應維持公開網址 `https://kuohuafan.github.io/susuai-pages/` 一致。

## 檔案

| 檔案 | 用途 |
|---|---|
| `index.html` | 公開品牌與文件首頁 |
| `styles.css` | 響應式視覺與排版 |
| `script.js` | 行動導覽、FAQ 與頁首狀態 |
| `404.html` | GitHub Pages 錯誤頁 |
| `robots.txt` | 搜尋引擎規則 |
| `sitemap.xml` | 公開網址索引 |
| `.nojekyll` | 要求 GitHub Pages 原樣提供靜態檔案 |

## References

[1]: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site "GitHub Docs — Creating a GitHub Pages site"
[2]: https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages "GitHub Docs — About GitHub Pages"
