"""This study utilizes a YOLOv8 detection model to identify fish in a video recorded from a fish tank.
A dataset consisting of 11 images of fish within the tank was uploaded to Roboflow, where bounding boxes were manually annotated around the fish in each image. These labeled images were then used to train a YOLOv8 model on a GPU. The training process was conducted over 3 epochs.
Upon completion of the training, a .pt file containing the trained model was generated. This model was subsequently applied to detect fish in the recorded video, which featured the same fish in the same tank. The detection code was executed to visualize the model's ability to identify the fish.
The model successfully detected fish throughout the video, demonstrating high performance under normal conditions. However, detection accuracy decreased during moments of significant blurriness in the video.
"""
