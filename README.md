# ML
機器學習


## Table of Contents
- Dowload dataset(下載資料)
- Importing Various Modules(匯入模組)
- Preparing the Data(準備數據)
- Choosing models(選擇模型)
- Evaluating the Model Performance(評估分析)
- Prediction(預測推論)

<!-- * [License](#license) -->


## 下載資料
-到kaggle網站下載flower資料集


## 模組匯入
-匯入所有需要用到的module(pandas,numpy,models....)


## 準備數據
- 讀取dataset
- 使用 train_test_split() 切割資料



## 訓練模型
1. training data 分為訓練集 and 測試集
2. 用 training data 訓練各模型
- 選擇 SVM,Random Forest,Decision Tree,KNN當model




## 評估分析
- 使用confusion matrix作分析
- 載入classification_report來看預測和實際數值的差異，包含precision、recall、f1-score及support,還有accuracy
- From the above models it can be notices that their accuracy is as follows

※※※
1. KNN Classifier - 92.83%, 在鄰居數量為21時有最好的表現
2. SVM Classifier - 96.83%
3. Random Forest Classifier - 86.67%
4. Decision Tree Classifier - 80.83%


## 預測推論
- 最後得出SVM的預測準確率最高





<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
