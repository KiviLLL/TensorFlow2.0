# TensorFlow2.0
• 南華大學-人工智慧期中報告  
• 11024156林昀皞  
# 目錄
•準備資源  
•實作方法  
# 準備資源
• 請準備一個可以使用google colab的帳號   
• 請下載附上的：tensorflow2.0.ipynb  
# 實作方法  
• 將使用Python在google colab進行以下操作：  
• 1.登入Google  
• 2.打開colab，並打開tensorflow2.0.ipynb並全部執行  
![img](https://github.com/KiviLLL/TensorFlow2.0/blob/main/img1.png)  
• 3.載入一個預先建置的資料集。  
     首先將TensorFlow 匯入到您的程式
     載入並準備MNIST 資料集。將樣本資料從整數轉換為浮點數   
![img](https://github.com/KiviLLL/TensorFlow2.0/blob/main/img2.png)  
• 4.建構對影像進行分類的神經網路機器學習模型。  
    透過堆疊層來建構tf.keras.Sequential模型。
    這個未經訓練的模型給出的機率接近隨機（每個類別為1/10），因此初始損失應該接近-tf.math.log(1/10) ~= 2.3。
![img](https://github.com/KiviLLL/TensorFlow2.0/blob/main/img3.png)  
• 5.訓練並評估模型的準確率。  
    使用Model.fit方法調整您的模型參數並最小化損失   準確度將近達到98% 
    想讓模型傳回機率，可以封裝經過訓練的模型，並將softmax 附加到該模型    
![img](https://github.com/KiviLLL/TensorFlow2.0/blob/main/img4.png)  
# 參考資料
https://github.com/tensorflow/docs-l10n/blob/master/site/zh-cn/tutorials/quickstart/beginner.ipynb
