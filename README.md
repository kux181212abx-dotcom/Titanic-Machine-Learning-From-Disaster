# Titanic-Machine-Learning-From-Disaster
大一電子的 Kaggle 初體驗：利用隨機森林模型預測鐵達尼號生還率。
# Titanic - Machine Learning From Disaster 🚢

這是我在 **大一** 時完成的第一個 Kaggle 數據分析專案。透過這個專案，我學習了完整的資料科學工作流，並克服了初學時的路徑配置與邏輯陷阱。

## 📊 專案亮點
- **模型選擇**: 使用隨機森林 (Random Forest) 進行分類。
- **特徵重要性**: 成功分析出 **Sex (性別)** 與 **Pclass (船票等級)** 是決定生還的最關鍵因素。
- **實戰紀錄**: 處理了 177 筆年齡缺漏值，並將類別資料轉換為電腦可識別的數值。

## 🛠 遭遇挑戰與解決
1. **路徑報錯 (FileNotFoundError)**: 
   - 學習使用 `os.walk` 偵測 Kaggle 環境下的正確檔案路徑。
2. **邏輯陷阱 (Sex Mapping Error)**: 
   - 發現重複執行 Mapping 會導致資料變成空值 (NaN)，進而影響模型判斷。透過重新載入原始數據並優化代碼流程解決。

## 📈 最終成績
- **Kaggle Score**: 0.68899
- **關鍵發現**: 雖然 "Lady First" 是歷史事實，但模型過度擬合 (Overfitting) 是未來優化的重點。
