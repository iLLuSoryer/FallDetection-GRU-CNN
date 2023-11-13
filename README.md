整體流程：
1. getNode：將圖片經由 Movenet 轉換成節點
2. keypointsTrain-CNN：將得到的節點交給 CNN model 訓練
3. NodeHaveTextVideo(eachFrame)：將要測試的影片交給訓練好的 CNN model 預測並輸出結果（影片）

注意：
* 要先將"DataPictures"內的"KeypointsWithoutFalldown.7z"和"withoutFalldown.7z"解壓縮
* "KeypointsWithoutFalldown"為"withoutFalldown"的節點資料，可以直接使用，這樣就可以跳過第一步驟（getNode）
* 所有路徑記得要修改

<video width="640" height="360" controls>
  <source src=r"C:\Users\ASUS\Desktop\school\project\FallDetection-GRU-CNN\movenetCNN\others.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
