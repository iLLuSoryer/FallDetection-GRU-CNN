__整體流程：__
1. getNode：將圖片經由 Movenet 轉換成節點
2. keypointsTrain-CNN：將得到的節點交給 CNN model 訓練
3. NodeHaveTextVideo(eachFrame)：將要測試的影片交給訓練好的 CNN model 預測並輸出結果（影片）

__注意：__
* 要先將"DataPictures"內的"KeypointsWithoutFalldown.7z解壓縮
* "KeypointsWithoutFalldown"為"withoutFalldown"的節點資料，可以直接使用，這樣就可以跳過第一步驟（getNode）
* 所有路徑記得要修改


__成品範例：__
![GIF示例](example.gif)
