# H24051045---FDA_HW2_Decision-Tree
利用 **Decision Tree** 的方法，分析年齡、職業、婚姻、教育程度、是否違約、收支平衡狀況、住宅、貸款、通訊設備、生日月份、生日日期、債券存續期間、運動頻率等資訊，預測是否有存款？

其中，變數的選取依照所計算出的相關係數矩陣，選取相關係數超越 +- 0.1 的變數，做為解釋變數。
最終，應用了 housing, loan, duration, campaign, pdays, previous 六個變數，在 Max_depth = 6 的 Decision Tree 中得出了最佳的預測結果為 0.77922！

另外，在最後不更改變數的情況下，嘗試應用其他分類器，包含 Random Forest、KNN 與 SVR，可惜結果不如預期，所得出的準確度僅介於 0.55 ~ 0.61，推測可能是因為這些分類器較不適用於類別型的資料。
