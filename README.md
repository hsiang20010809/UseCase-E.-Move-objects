## 繼 OOAD_UseCase_D_Group_objects 的續做

新增功能:

## Move objects

操作流程：

1. 點擊 Select 按鈕，在編輯地區的某個基本物件（包含 composite 物件）範圍內按下 mouse 的左鍵，但是不放開(mouse pressed) 。
2. 使用者不放開左鍵，進行拖曳(drag)的動作。
3. 使用者拖曳到另外一個座標 x,y 放開左鍵 (mouse released) 。
4. 該基本物件被移動到新座標 x,y 。
5. 所有連結到該基本物件的 connection links 全部重新繪製。

## 修復與優化

群組物件的子物件選取狀態修復:

1. 修正群組物件中的子物件選取邏輯，確保相應地更新子物件的實際選取狀態。

2. 新增Link模式，並將連線按鈕從下拉式清單獨立出來，繪圖方式由SELECT按鈕轉為使用連線(association, generalization 以及 composition)按鈕

## 更新摘要

懶得寫了，來去洗澡睡覺，這次不知道又燒了幾根頭毛