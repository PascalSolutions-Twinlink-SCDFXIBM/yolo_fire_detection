# yolo_fire_detection
People Counter and Fire Detection using YOLOv3
![alt text](Prototype.png)

The YoloV3 weights trained on the COCO dataset

# <u><center> HOW TO USE THIS </center></u>
### <u>1. First download the weights to .\Data\Model_Weights</u>
####   - Download the weights here: https://entuedu-my.sharepoint.com/:u:/g/personal/lchan017_e_ntu_edu_sg/EWjUUTdPzrBGgxBtj-16wBEBu5hjpZWClFlpHW5wf7ptNw?e=FaBdFQ
####   - This weights are retrained versions of the original YOLOv3 From: https://pjreddie.com/darknet/yolo/
####   - The original framework is converted to keras by: https://github.com/AntonMu/TrainYourOwnYOLO

### <u>2. Run the Notebook:</u>
####   - Yolov3 Dependencies should be in the same folder as the notebook before running
####   - The Following Line in the notebook will process videos ,
![alt text](IMG1.png)
####   - Drag your own video to be analysed to the same folder as this notebook (here its "cctv_4.mp4") under "video_path"
####   - Set your output directory under "output_path"
####   - Once the video has been processed, a labeled video should be created in the output path
