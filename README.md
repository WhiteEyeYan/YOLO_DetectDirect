# YOLO_DetectDirect
語言：python  
程式最後修改時間：2020/09/02  
  
遊戲中有時後需要玩家依序輸入上下左右後才能解除負面效果  
上下左右每次形狀、顏色皆不同，有時候又會半透明化，造成肉眼判定不易  
就算肉眼判斷無誤又可能會按錯  
  
所以用yolo及修改作者的darknet.py來判斷上下左右且由左至右排序找到的物件，再依序輸入解除負面效果  
  
訓練效果：  
  
  example 1：  
  ![img](https://github.com/WhiteEyeYan/YOLO_DetectDirect/blob/main/README_img/original_1.jpg) ![img](https://github.com/WhiteEyeYan/YOLO_DetectDirect/blob/main/README_img/result_1.jpg)  
  
  example 2：  
    ![img](https://github.com/WhiteEyeYan/YOLO_DetectDirect/blob/main/example_img/original_2.jpg) ![img](https://github.com/WhiteEyeYan/YOLO_DetectDirect/blob/main/README_img/result_2.jpg)  
  
  example 3：  
  ![img](https://github.com/WhiteEyeYan/YOLO_DetectDirect/blob/main/example_img/original_3.jpg) ![img](https://github.com/WhiteEyeYan/YOLO_DetectDirect/blob/main/README_img/result_3.jpg)  
