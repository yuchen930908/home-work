# 0328

## 簡介
這是一個簡單的 Arduino 專案，使用按鈕控制 LED 和蜂鳴器的開關。

## 硬體需求
- Arduino 開發板
- 按鈕
- LED
- 蜂鳴器
- 連接線

## 接線方式
- 按鈕連接到數位腳位 7，並啟用內建上拉電阻。
- LED 連接到數位腳位 13。
- 蜂鳴器連接到數位腳位 2。

## 程式邏輯
1. 初始化時，設定 LED 和蜂鳴器為輸出模式，按鈕為輸入模式並啟用內建上拉電阻。
2. 在主迴圈中，持續讀取按鈕的狀態：
   - 如果按鈕被按下 (狀態為 LOW)，點亮 LED 並啟動蜂鳴器。
   - 如果按鈕未被按下，關閉 LED 和蜂鳴器。

## 使用方式
1. 將程式上傳到 Arduino 開發板。
2. 按下按鈕，觀察 LED 點亮和蜂鳴器啟動。
3. 放開按鈕，LED 和蜂鳴器將關閉。

## 程式碼
請參考 `0328` 檔案中的程式碼。