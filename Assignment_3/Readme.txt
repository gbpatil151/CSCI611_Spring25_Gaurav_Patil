best.pt								Fine-trained model by dataset
GX011171_output_video.mp4			Video using best.pt - link present in report
yolov8n.pt							Pre-trained model
GX011171_output_video_stock.mp4		Video using yolov8n.pt - link present in report
results.csv							Data during each epoch
A3_611.ipynb						Jupyter notebook file
output_image_train_stop.jpg			Image using best.pt 
output_image_yolo_stop.jpg			Image using yolov8n.pt
Report_A3.pdf						Assignment report




Project Workflow Overview (A3_611.ipynb)

Importing Required Libraries
The project begins by importing essential libraries, including Roboflow, OpenCV, and PyTorch, to facilitate dataset handling, image processing, and model training.

Dataset Acquisition
The Self-Driving Car Dataset is downloaded from Roboflow and preprocessed for compatibility with YOLOv8.

Model Training
A pre-trained YOLOv8n model is loaded and fine-tuned on a traffic sign dataset, focusing on detecting traffic lights, stop signs, and road markers.

Video Processing with the Fine-Tuned Model
The trained model is applied to video data using two approaches:

Direct Video Processing: Runs YOLOv8 directly on the entire video, saving results to output.mp4. However, this resulted in increased video size and altered duration, likely due to frame rate discrepancies.
Frame-by-Frame Processing: Each video frame is processed individually, similar to image-based inference, and then reconstructed into a video. This method preserved the original video length but resulted in a larger file size.
This workflow ensures effective small object detection while identifying challenges in video processing and model fine-tuning.