整體流程：
1. getNode：將圖片經由 Movenet 轉換成節點
2. keypointsTrain-CNN：將得到的節點交給 CNN model 訓練
3. NodeHaveTextVideo(eachFrame)：將要測試的影片交給訓練好的 CNN model 預測並輸出結果（影片）

注意：
* 要先將"DataPictures"內的"KeypointsWithoutFalldown.7z解壓縮
* "KeypointsWithoutFalldown"為"withoutFalldown"的節點資料，可以直接使用，這樣就可以跳過第一步驟（getNode）
* 所有路徑記得要修改



https://github.com/iLLuSoryer/FallDetection-Movenet-CNN/assets/91926628/f7262b42-c99e-4a5c-b373-4d7b323ced4c

