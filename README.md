# Kaggle-Ghouls-Goblins-and-Ghosts...-Boo!
## 步驟
**一、觀察資料、資料預處理**
1.	觀察訓練集<br/>
(1) 檢查訓練集資料的空值<br/>
(2) 觀察訓練集的描述性統計資料<br/>
(3) 觀察訓練集的變量關係：bone_lenth與hair_length、bone_lenth與has_soul、hair_length與has_soul有正向關係<br/>
 
2.	觀察測試集<br/>
(1) 檢查測試集資料的空值<br/>
(2) 觀察測試集的描述性統計資料<br/>
(3) 觀察測試集的變量關係<br/>
 
3.	對類別特徵進行編碼：color及type<br/>
(1) 將color編碼："blood":1, "blue":2, "black":3,"green":4,"clear":5,"white":6<br/>
(2) 將type編碼："Ghoul":3, "Goblin":2, "Ghost":1<br/>

**二、建立及訓練模型、挑選演算法**<br/>
1. 羅吉斯回歸<br/>
2. 隨機森林<br/>
3.	SVM<br/>
4.	KNN<br/>
5.	AdaBoost<br/>

**三、選擇準確度最高方法，並整理輸出格式**

**四、上傳Kaggle評分**
