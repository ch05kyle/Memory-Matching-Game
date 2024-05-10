 # Memory-Matching-Game

 # 1. HTML結構 (詳細)
- 創建一個HTML標題，標題的文字內容為 "Memory Matching Game"，讓用戶可以在瀏覽器的標題欄中看到
- 在頁面的頂部，創建一個標題區域，區域中央有一個大字體的文字 "Memory Matching Game"，明確告訴用戶這是一個記憶配對遊戲
- 主要內容區域包含以下元素：一個4x4的遊戲網格，用於顯示和操作遊戲卡片；一個消息顯示區，用於向用戶展示遊戲的進度和結果；一個重啟遊戲按鈕，用戶可以點擊此按鈕來重新開始遊戲
- 在頁面的底部，創建一個頁腳區域，區域中央有一個小字體的文字，用於顯示遊戲的版本信息

 # 2. CSS樣式
- 利用background-color設定背景為藍色
- 要有黃色四乘四方格去顯示emoji
- 增添一個重設按鈕,遊戲完成時便可以按下去

# 3. JavaScript邏輯
- 首先頁面一登入,顯示4x4的方格,然後有8對emoji隨機在這方格內顯示大概五秒
- 五秒後他們自動翻牌,要將這8對emoji隱藏,然後玩家要憑記憶去按下該8對emoji
- 安完後有個視窗顯示你完成,當玩家按重設按鈕時變重新開啟遊戲
