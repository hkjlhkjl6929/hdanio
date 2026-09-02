H'DANIO 廣告成效報表

檔案用途
- index.html：前台與後台共用主程式
- data/links.sqlite：短網址資料庫
- robots.txt：避免搜尋引擎索引

部署方式
1. 建立或打開 GitHub repo：hkjlhkjl6929/hdanio
2. 把 index.html、robots.txt、data/links.sqlite 上傳到 repo 根目錄
3. 到 Settings → Pages，將 main branch 設為 GitHub Pages 來源
4. 後台網址會是：https://hkjlhkjl6929.github.io/hdanio/

後台使用
1. 打開後台網址
2. 到「資料設定」匯入 H'DANIO 的 Meta CSV
   建議欄位：creative_id、spend、impressions、link_clicks、purchases、purchase_value、target_cpa、target_roas
3. 確認欄位對應與分組
4. 儲存為月份
5. 設定 GitHub Token、Repo owner、Repo、客戶代號 hdanio
6. 按「複製業主版連結」

前台給業主
- 後台按「複製業主版連結」後會產生短網址，例如：
  https://hkjlhkjl6929.github.io/hdanio/?s=xxxxx

注意
- H'DANIO 這版固定使用 TWD 台幣，不做外幣換算。
- data/links.sqlite 已初始化為空資料庫，沒有沿用達特療短碼。
- 素材成效會依 creative_id 彙整，並依成熟素材、潛力素材、待觀察素材、建議停用素材排序。
