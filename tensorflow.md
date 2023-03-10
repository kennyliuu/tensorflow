# Tensorflow2初學篇
    Author：劉家誠
    Date：2022/12
---
## 一、第一章 人工智慧、機器學習、深度學習介紹
#### 1.1 人工智慧介紹
+ 圖靈測試：
    + 人類與機器通過電傳設備對話。
    + 若人類無法從對話過成判斷對方是機器或人類，則機器通過測試並具有人工智慧。
+ 人工智慧分類：
    + 強人工智慧：機器具有與人類完整相同的認知和智慧能力。
    + 弱人工智慧：機器不具有與人類完整相同的認知和智慧能力，只在某些特定領域具有智慧。 
        > 目前AI均屬弱人工智慧。   
---
#### 1.2 機器學習介紹
+ 機器學習分類：
    ![Alt text](https://img.onl/Ei8Fkz)

+ 機器學習：監督式學習(分兩階段)
    ![superevised](https://img.onl/U9RFN)
    + 訓練階段：把累積的資料經過feature extraction，產生feature和label,再透過演算法訓練後產生模型。
    + 預測階段：產生模型後輸入新的資料再經過feature extraction 產生特徵，並用訓練好的模型做預測，最後得到預測結果。   
    
+ 機器學習：非監督式學習(只有特徵沒有標籤，只能從特徵找到規律)
    ![unsuperevised](https://img.onl/2tNsRJ)
     > 只有特徵沒有標籤，只能從特徵找到規律
---
#### 1.3 深度學習介紹
+ 深度學習模型跟其他機器學習模型像是單純貝氏分類器或svm,最大的區別就是深度學習模型資料量越大，表現會越好，當資料量不大時表現比較普通甚至其他模型可能比較好，但是資料量一旦上去差別就很明顯。
