## PERT 圖&&關鍵路徑
![NKUST](https://github.com/C110118135/20230918/blob/main/pert_diagram%20%E7%9A%84%E5%89%AF%E6%9C%AC%20(1).jpg "NKUST")

## 甘特圖
### Mermaid
```mermaid
gantt
    title 任務清單
section 1
    研礙計劃           :a1, 2023-09-01, 1d
section 2
    任務分配           :a2, after a1  , 4d
section 3
    取得硬體           :a3, after a1  , 17d
section 4
    程式開發           :a4, after a2  , 70d
section 5
    安裝硬體           :a5, after a3  , 10d
section 6
    程式測試           :a6, after a4  , 30d
section 7
    撰寫使用手冊        :a7, after a5  , 25d
section 8
    轉換檔案           :a8, after a5  , 20d
section 9
    系統測試           :a9, after a6  , 25d
section 10
    使用者訓練         :a10, after a7  , 20d
section 11
    使用者測試         :a11, after a9  , 25d
``` 
