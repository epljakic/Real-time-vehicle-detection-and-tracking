# Real-time-vehicle-detection-and-tracking

The system is able to detect and track vehicles in real time.
This system goes through these steps for each incoming frame:
- Creates 4 regions of interest with different scaling factors in which the features are extracted.
- Extracts features based on a histogram of oriented gradients (HOG) for each block.
- Detects whether there is a vehicle in that block or not using support vector machine (SVM).
- Returns an input frame with marked regions where vehicles have been detected.

![](https://github.com/epljakic/Real-time-vehicle-detection-and-tracking/blob/main/31.result_test_img.png)
