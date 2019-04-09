# 失落的龍絆 資源追蹤及掉落一覽表

使用者可以利用這份EXCEL檔案觀看掉落及追蹤手邊資源，歡迎自行下載，有需要時也可以自行修改。

### 電腦
點選`Dragalia Data.xlsx`以後，點選右上角`Download`下載。

### 手機
點選`Dragalia Data.xlsx`以後，點選內容區塊的`Open binary file`下載。

----

未來預計:
- **[取消]** 轉為網站

----

## 自行輸入欄位 - 任何粗體字的地方

### 迎擊
- **[C2:C11,C14:C16]** 輸入目前擁有的道具的對應數量
### 真龍
- **[J3:J7]** 輸入對應屬性的真龍珠的擁有數量
### 龍之試煉
- **[B3:B5]** 輸入擁有的龍果數量
- **[D3:D5]** 輸入要預先扣除計算之外的龍的等級經驗
### 虛空
- (無)
### RAID
- **[B1:B2]** 活動的開始和結束時間
- **[E5:E6]** 活動目標金章、戰貨
- **[A-LAST:B-LAST:C-LAST]** 輸入目前時間和目前進度，然後複製右上的所有公式至同一行
- **[J:J]** 以起始時間所對應的欄位號碼做為參考點，計算假設等速度下，預計趕上進度的時間點

## 自行輸入掉落資料

### 迎擊
- **[R2:X3]** 
1. 輸入農前農後的素材量
2. 記下各道具的**掉落數量**和**場次**
3. 根據道具和屬性迎擊輸入資料到`資料-迎擊`裡面
> - 前五組顏色代表五種屬性，後面三組顏色代表金、銀、銅幣
> - 平均會自己計算，複製上方公式以計算平均即可

### 超龍
- **[K2:P3]**
1. 輸入農前農後的素材量
2. 記下**獲得經驗**和**場次**
3. 到`資料-龍試煉`輸入資料
> - 平均會自己計算，複製上方公式以計算平均即可

### 虛空
- **[F2:K3]**
1. 輸入農前農後的素材量
2. 記下各道具**掉落數量**和**場次**及該記錄所打的BOSS
3. 根據道具和屬性迎擊輸入資料到`資料-虛空`裡面

### 掉落-真X
- 到對應的真龍工作表裡面，直接輸入掉落的真龍珠數量即可
> 未釋出的真龍表格是隱藏的，後續釋出未更新表格的話，要自己解除隱藏

----

> - 如果你跟我一樣有時候連打10+小時，中途會想看看刷了多少但是不紀錄，先繼續打的話，可以直接輸入農後的素材量但是不更新掉落資料。
> - 可以的話，盡可能的減少`資料-**`中紀錄原始掉落資料的行數(壓縮資料)，以避免過多重複運算。

----

## 已知問題
- (無)
