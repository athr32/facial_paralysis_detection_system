# facial_paralysis_detection_system

Digital Image Processing Lab Project

Developed a computer vision–based system to detect facial paralysis using deep learning for objective and early diagnosis support.

Designed the complete end-to-end pipeline, from problem formulation to model training, testing, and result visualization.

Created a custom dataset by collecting facial images and manually labeling them into two classes: Normal and Paralysis.

Performed dataset annotation using Roboflow, generating bounding boxes and exporting data in YOLO format.

Trained a YOLOv8m object detection model (pretrained on COCO) using Google Colab, leveraging transfer learning for better performance on limited data.

Applied data augmentation, early stopping, and hyperparameter tuning (epochs, batch size, image size) to reduce overfitting.

Implemented a real-time detection pipeline using OpenCV to visualize bounding boxes, class labels, and confidence scores on images/videos.

Achieved 86.32% accuracy on the test dataset, successfully distinguishing between normal and paralyzed facial regions.

Analyzed training and validation performance using accuracy vs epoch curves to evaluate model convergence.

Identified project limitations such as small dataset size and proposed future improvements including dataset expansion and mobile deployment.

Demonstrated the potential for real-world medical and commercial applications, including assistive diagnostic tools for hospitals.
