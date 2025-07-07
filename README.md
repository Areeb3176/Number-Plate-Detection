DESCRIPTION: this is the repository of anpr project which is used to detect number platers from a video and read text from  it.
REQUIREMENTS: following are the things u need to download run this project
1) opencv
2) easy ocr
3) sort repository from https://github.com/abewley/sort
4) you also need to make test.csv and interpolated.csv using csv.py

This project focuses on detecting vehicles and recognizing license plate numbers in video footage using deep learning and computer vision techniques. It integrates YOLOv8, a state-of-the-art object detection model, with SORT, a real-time tracking algorithm, to accurately track vehicles and extract number plates across video frames.The system first uses YOLOv8 to detect vehicles, and then applies a custom-trained YOLOv8 model to detect license plates. Each detected license plate is cropped, preprocessed using OpenCV (grayscale conversion and thresholding), and passed through an OCR function to read the text. The SORT tracker ensures consistent vehicle ID assignment across frames. Finally, the detected results, including vehicle positions and license plate numbers, are saved into a CSV file for further analysis or reporting.This solution demonstrates how object detection, tracking, and OCR can be combined effectively for intelligent traffic monitoring and surveillance applications.
