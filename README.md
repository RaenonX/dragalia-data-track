# 失落的龍絆 資源追蹤表
### 電腦
點選`Dragalia Data.xlsx`以後，點選右上角`Download`下載。

### 手機
點選`Dragalia Data.xlsx`以後，點選內容區塊的'Open binary file`下載。

----

未來預計:
- 新增虛空素材計算
- 轉為網站

----

## 自行輸入欄位
### 迎擊
- 擁有欄位輸入目前擁有銀章數量
- 下半部輸入建築等級
### 真龍
左下區塊
- 已有
- 建築等級
- 龍突破
### 超龍
- "數量"區塊，根據龍果大小輸入
- "預扣"，留全空代表不預扣

## 自行輸入掉落資料
### 迎擊
1. 到`Tools`工作表內輸入 刷前 和 刷後 的 翅膀數量、鑽石數量和銀章數量，獲取你刷出掉3或掉4的場次數目
2. 到`_DataIO`工作表裡面，根據你的迎擊屬性的顏色，在對應的欄位輸入掉3或掉4的資料
### 真龍
真龍簡寫對照表

| 中文      | 真龍簡寫 | 英文全名 |
| :-: | :-: | :-: |
| 真火      | HBrun       | High Brunhilda |
| 真水   | HMerc        | High Mercury |
| 真風      | HMid       | High Midgarsormr |
| 真光   | HJup        | High Jupiter |
| 真暗      | HZod       | High Zodiac |

 到名為`_Data{真龍簡寫}`的資料表內(橘色底色)內，輸入單場掉落珠的數字。可以參考真火、真風的輸入方式。
> 未釋出的真龍表格是隱藏的，後續釋出未更新表格的話，要自己解除隱藏
### 超龍
1. 到Tools裡面龍的試煉區塊，輸入 刷前 和 刷後 的 鑽量、翅膀數目、小中大龍果數目
2. 把算好的獲得經驗跟場次貼到_DataDragonEXP(藍底)的工作表裡面

----

> 如果你跟我一樣有時候連打10+小時，中途會想看看刷了多少但是不紀錄，先繼續打得話，可以先把Tools裡面的LAST UPDATE右邊的公式NOW()複製起來，然後在原位選擇貼上"值"，等刷爽了再把NOW()換回來

----

## 已知問題
- 目前完全沒有超龍的資料，沒有辦法估一條60等、80等、100等要多少素材，使用者需要自己輸入
