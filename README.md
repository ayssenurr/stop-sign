#  Stop Sign Detection Project

This project demonstrates object detection on stop signs using a custom YOLOv5 model.  
Dataset was prepared via Roboflow and trained in Google Colab.

## Files

- `stop_sign_project.ipynb`: Full Colab notebook for training and detection  
- Trained model weights saved under: `runs/train/exp4/weights/best.pt`  
- Sample predictions in: `runs/detect/exp3/`

## Model

- Model: YOLOv5s  
- Input Size: 416x416  
- Trained on 1 class: `stop_sign`  
- Epochs: 10  
- Batch Size: 16

## Results

Detection results show successful identification of stop signs with high confidence:

![Example](runs/detect/exp3/sample.png) ← (You can upload and link an example image if you want)

---

## Requirements

```bash
torch>=1.7
opencv-python
matplotlib
