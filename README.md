# Data_analytics
* Personal Project
* python
## Billboard "The Hot 100" Songs 分析
* 數據來源Kaggle的"Billboard "The Hot 100" Songs"
* 數據蒐集的時間為1958年到2021年間的數據
* 欄位名稱其意義為: date: Date of chart; rank: Rank of song; song: Song title; artist: Song artist; last-week: Rank in previous week; peak-rank: Top rank achieved by the song; weeks-on-board: Weeks the song appeared on the chart
* 數據處裡的目標: 
1. 處理last-week空值。
2. 2020年有多少新歌。
3. 2020年每個月的新歌。
4. 2020年有哪些新歌進榜就拿到第一名。
5. 前10首在Billboard停留時間最久的歌。
6. 獲得最多次第一名的歌手。
7. 上榜最多次的藝人。
## 數據分析HW
* 數據來源Kaggle的"Superstore Sales Dataset"
* 數據蒐集的時間為2015年到2018年間的數據
* 欄位名稱其意義為:order_id：該筆訂單的代號; Order Date:該筆訂單日期 ; Ship Date:該筆訂單運送日期; Ship Mode:該筆訂單運送方式; Customer ID：該筆顧客的代號; Customer Name:該筆顧客的代號 ; Segment：該筆訂單購買的顧客屬於哪種市場; Country:該筆訂單的國家 ; City:該筆訂單的城市 ; State:該筆訂單的州 ; Postal Code:該筆訂單的郵遞區號 ; Region:該筆訂單的地區 ; Product ID：該筆訂單購買商品內容的代號; Category：該筆商品所屬的分類; Sub-Category:該筆商品所屬的子分類 ; Product Name：該筆分類的名稱; Sales：該筆總消費金額。
* 數據處裡的目標: 
  - 處理Postal Code中的空值。
  - 客戶分析
    1. RFM分析。
      - 計算每個顧客其最近一次消費距今的天數(recency)
      - 計算每個顧客消費的頻率並取得消費頻率的統計量描述(frequency)
      - 計算每個顧客消費總額的統計量描述(monetary)
      - 整合並構建處理後的數據表格以利後續數據分析
      - 顧客分類
    2. 找出消費金額最大的顧客。
  - 區域分析
    1. 找出哪些州創造了最高的收入。
    1. 找出哪一座城市創造了最高的收入。
    1. 哪個地區銷售額最高。
  - 產品分析
    1. 分析每個類別的銷售。
    1. 哪些產品對收入的貢獻最大。
    1. 每個子類別的銷售。
  - 銷售分析
    1. 分析不同市場的銷售。
    1. 相關性Heatmap視覺化圖。
    1. 整體銷售情況分析。
