## 數據前處理：  
使用Pandas進行數據加載與初步探索，利用NLTK去除停用詞，並對文本進行清理和向量化，為模型訓練做好準備。

## 視覺化分析：  
生成文字雲以視覺化真假新聞中最常見的詞彙。  
真新聞  
<img width="799" alt="截圖 2024-03-31 下午8 38 07" src="https://github.com/choushihche/fake_news-LSTM/assets/82157437/783b9c8b-329e-4403-a5a2-2f854aa0bf01">  
假新聞  
<img width="799" alt="截圖 2024-03-31 下午8 40 05" src="https://github.com/choushihche/fake_news-LSTM/assets/82157437/2323057a-a9c2-4398-84ea-8e32758f3107">

## 嵌入矩陣構建：  
利用GloVe預訓練詞向量建立嵌入索引，並創建嵌入矩陣，為LSTM模型提供豐富的語義訊息。

## 模型構建與訓練： 
設計含嵌入層、LSTM層、Dropout層和Dense層的深度學習模型，使用Keras框架實現，並通過驗證集監控訓練進度。

## 性能評估：  
繪製準確率與損失值曲線圖，評估模型在訓練及測試集上的表現，有效識別過擬合或欠擬合現象。  
![messageImage_1711888818108](https://github.com/choushihche/fake_news-LSTM/assets/82157437/b0e1e622-fe7c-48f9-a427-6be2d4c2e26c)
![messageImage_1711888822105](https://github.com/choushihche/fake_news-LSTM/assets/82157437/fbf403b6-8e9a-416e-babd-3b48bb4a806d)
