# 作業說明（README）

> 本作業以**預測汽車油耗（mpg）**為主題。請從 `sample_code.ipynb` 起步，熟悉資料與評估流程，依規則完成 baseline 與模型改進，並撰寫報告。

---

## 1) 作業介紹

- **任務**：根據車輛相關資訊預測油耗 **mpg**（回歸問題）。
- **評估指標**：**RMSE（Root Mean Squared Error）**。所有分數均以評測平台的結果為準。
- **實作重點**
  1. 讀取並理解資料；完成必要的清理與轉換  
  2. 建立合適的回歸模型並進行本地驗證  
  3. 產出正確格式的提交檔上傳評測  
  Kaggle網址：https://www.kaggle.com/t/051b440f948046e29fbffaf134dbafeb
- **起始範例**：`sample_code.ipynb` 提供最小可行流程（讀檔、簡單前處理、模型訓練、輸出提交）。你需要在此基礎上自行改進。

---

## 2) 資料集與特徵

- **檔案結構**
  ```
  data/
    ├─ train.csv      # 訓練資料（含 mpg 目標欄位）
    └─ test.csv       # 測試資料（不含 mpg）
  sample_code.ipynb
  ```

- **欄位概述**
  * `id`: 唯一識別碼
  * `mpg`: **(預測目標)** 每加侖英里數 (Miles Per Gallon)，代表燃油效率。
  * `cylinders`: 汽缸數
  * `displacement`: 排氣量
  * `horsepower`: 馬力
  * `weight`: 車重
  * `acceleration`: 加速度
  * `model_year`: 製造年份 (例如：70 代表 1970 年)
  * `origin`: 產地 (1: 美國, 2: 歐洲, 3: 日本)
  * `name`: 車款名稱

---

## 3) 評分規則（總分 12 分）

1. **Simple Baseline（3 分）**  
   - 依作業說明完成**必要的輕量改動**與基本前處理，並**通過 public easy baseline**。

2. **Medium Baseline（3 分）**  
   - 在簡單基線之上做**更完整的調整／特徵設計／模型設定**，並**通過 public medium baseline**。

3. **報告（6 分）**  
  - 第一部分：準確度分數 (Accuracy Scores) (1分)  
  - 第二部分：我的實驗記錄 (My Experiment Log) (3分)  
  - 第三部分：總結與心得 (Conclusion & Reflection) (2分)  
  （請參考`sample_code.ipynb`的報告部分）
