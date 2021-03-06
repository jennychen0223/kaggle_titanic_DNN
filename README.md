# Kaggle經典競賽題目：鐵達尼號生存預測
## 專案介紹

1. 本專案目的為藉由乘客資訊（乘客的性別、姓名、出發港口、住的艙等、票的費用、票的號碼...等），與目標變數是否生存，來進行分類的模型預測。
2. 此Kaggle題目為競賽型題目，且持續進行中，可將最後預測的結果上傳取得排名，目前已有86,179組參賽者的成果，可說是競爭相當激烈的一道題目

## 成果

- 總參加人數：89,457
- 排名：17,438 (前19.4%)
後續可再思考其他資料處理方式及不同模型及參數設定來提高準確率！

![image](https://user-images.githubusercontent.com/81677812/128609218-1f75f572-684a-43e4-94e4-b3dab0a1bc51.png)
![image](https://user-images.githubusercontent.com/81677812/128609220-3c40aa71-bf4d-4add-8415-22858c6faba8.png)

## 資料來源

本次資料是利用Kaggle平台釋出作為開放性議題，提供參賽者建立分類模型進行預測。
（Titanic - Machine Learning from Disaster）

資料來源：https://www.kaggle.com/c/titanic/code

## 專案步驟：

- 了解資料
- 資料前處理
- 建立模型
- 模型評估

## 了解資料

1. 訓練資料：891筆、12個欄位
2. 測試資料：418筆、11個欄位
3. 圖示化分析特徵變數與目標變數相關性


## 資料前處理

1. 處理空值：觀察與空值欄位有高相關性者欄位，進行補值
2. 建立新欄位：萃取Name的稱謂，並建立新欄位
3. 資料清洗：刪除不重要欄位（Name）
4. 類別型資料：將文字mapping成0,1,2...
5. 數值型資料：分佈較離散的欄位做區間化
6. 特徵值標準化，使數值介於0-1之間

## 建立模型

1. 設定預測目標變數與解釋變數
2. 利用Keras的套件建立DNN模型

## 模型結果
<img width="412" alt="image" src="https://user-images.githubusercontent.com/81677812/128303692-3ea6f207-a38f-4bb9-9cef-3de0f926251d.png">

