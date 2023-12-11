# Poker-Card-Detection-Tracking
Using Convolutional Neural Networks to detect poker playing cards

## <u>Overview</u>
The main objective of this project is to develop a classification algorithm that correctly identifies individuals with heart disease based on some of their health condition and other relevant attributes. To achieve that several classifiers were trained on a labelled dataset of patients, as well as ensemble methods, boosting and stacking methods. Results from all these methods were thoroughly analysed and the advantages and disadvantages of each of the methods used were rigorously discussed. The classifier that was ultimately selected was the one that achieved the best balance between performance and interpretability.

## <u>About the dataset</u>

The Playing Cards dataset is a collection of synthetically generated cards blended into various types of backgrounds. You will be able to perform object detection to detect both number and suit of the cards. The dataset contains 10100 images that were preprocessed and augmented resulting in a total of 24240 which were consequently split into 21210-2020-1010 for training, validation and testing respectively. 

### Preprocessing:
- Auto-Orient: Applied
- Resize: Stretch to 640x640

### Augmentations
Outputs per training example: 3
- Flip: Horizontal, Vertical
- 90° Rotate: Clockwise, Counter-Clockwise, Upside Down
- Crop: 0% Minimum Zoom, 15% Maximum Zoom
- Rotation: Between -10° and +10°
- Shear: ±2° Horizontal, ±2° Vertical
- Grayscale: Apply to 10% of images
- Hue: Between -25° and +25°
- Saturation: Between -25% and +25%
- Brightness: Between -25% and +25%
- Exposure: Between -15% and +15%
- Blur: Up to 1.75px
- Noise: Up to 2% of pixels
- Cutout: 5 boxes with 2% size each
[roboflow playing card dataset]([https://github.com/ultralytics/yolov5](https://universe.roboflow.com/augmented-startups/playing-cards-ow27d/dataset/4)https://universe.roboflow.com/augmented-startups/playing-cards-ow27d/dataset/4]
