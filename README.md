# Hotel-housing-analysis

預測訪客是否會訂房，依照流量統計資料train.csv，訓練一個分類模型或回歸模型，
預測test.csv中每位訪客是否會進行消費的機率，並依照sample_submission.csv的格式提交預測結果。

記錄資料分析、清理、建模、模型評估的過程

* 屬性說明：
	- Administrative：管理頁面瀏覽數量
	- Administrative_Duration：管理頁面瀏覽時間
	- Informational：資訊頁面瀏覽數量
	- Informational_Duration：資訊頁面瀏覽時間
	- ProductRelated：產品頁面瀏覽數量
	- ProductRelated_Duration：產品頁面瀏覽時間
	- BounceRates：跳出率
	- ExitRates：退出率
	- PageValues：頁面價值
	- SpecialDay：特殊日期（例如聖誕節，情人節）接近程度
	- Month：訪問月份
	- OperatingSystems：作業系統
	- Browser：瀏覽器
	- Region：地區
	- TrafficType：流量來源
	- VisitorType：訪客類型
	- Weekend：訪問時間是否為週末
	- Revenue：是否訂房
