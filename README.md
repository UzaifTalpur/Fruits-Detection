# Fruits Detection
🚀 Are you passionate about leveraging cutting-edge technology to solve real-world problems? Look no further! I’m excited to introduce **Fruits Detection**, a TensorFlow Lite object detection project built on the foundational work by Edje Electronics and designed to detect fruits with precision using Google Colab.

## Project Overview
This project utilizes TensorFlow Lite and reinforcement learning techniques to detect and classify different types of fruits such as **apples, bananas, and oranges**. Initially based on Edje Electronics' coin detector project, I customized the model by training it on a new fruit dataset, enabling efficient fruit detection for practical applications.

## Dataset
- **Source**: [Kaggle - Fruit Images for Object Detection](https://www.kaggle.com/datasets/mbkinaci/fruit-images-for-object-detection)
- **Author**: Muhammed Buyukkinaci, Kaggle Expert, Istanbul, Turkey
- **Details**: The dataset includes images of various fruits, providing a robust foundation for building a reliable object detection model. Images were annotated using **LabelImg** to create bounding boxes, ensuring accurate model training.

## Training and Model
- **Platform**: Google Colab
- **TensorFlow Lite Object Detection API**: Adapted from the [TensorFlow Lite Object Detection API by Edje Electronics](https://github.com/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi).
- **Customizations**: This model was retrained with a custom fruit dataset, leveraging TensorFlow Lite’s lightweight architecture to enable quick and efficient fruit recognition on mobile and embedded devices.
  
## How It Works
The model is trained to recognize the following fruits:
- 🍎 **Apple**
- 🍌 **Banana**
- 🍊 **Orange**

By replacing the original dataset with fruit images and tuning the model parameters, the system achieves a detection accuracy of 95-97%. This makes it an excellent tool for applications in:
- **Smart Grocery Sorting**: Identify fruits in real-time for inventory management.
- **Agriculture Monitoring**: Detect and classify fruits in the field.
- **Dietary Apps**: Use smartphone cameras to identify fruit types for nutritional tracking.

## Installation
1. **Visit The Collab Master File**:
    ```You just have to follow the step by step guide
    ```
2. **Set up Google Colab for Training**:
   Open the Colab notebook and execute it according to your dataset.

3. **Install Dependencies**:
   Make sure you have the required libraries by running:
    ```Make sure the virtual connection does not get disrupt as it will halt the training in midway process.
    ```

## Usage
1. Upload your dataset to Google Colab.
2. Set up TensorFlow Lite and start the training with custom fruit images.
3. Download the trained model and deploy it to your desired device.

## Results
![Fruit Detection Sample](media/)
The model’s accuracy ranges from 95% to 97%, based on testing with varied lighting and backgrounds. This can verified on my LinkedIn post mentioned at media/ section of Project Strucure below.

## Project Structure
- `src/`: Main scripts for training and detection "https://colab.research.google.com/github/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi/blob/master/Train_TFLite2_Object_Detction_Model.ipynb".
- `docs/`: Technical documentation and annotated dataset details."https://youtu.be/XZ7FYAMCc4M?si=-f3ZH17552Y3lxSn"
- `media/`: Contains images and screenshots of detected fruits. "https://www.linkedin.com/posts/uzaif-talpur_fruitsdetection-technology-computervision-activity-7084097366751948801-O1IZ?utm_source=share&utm_medium=member_desktop"
- `models/`: Pre-trained models and trained weights. "https://github.com/tensorflow/models/tree/master/research/object_detection"

## Acknowledgments
Thanks to **Edje Electronics** for their open-source contributions to TensorFlow Lite object detection, and **Muhammed Buyukkinaci** for the Kaggle dataset that made this project possible.
You can access the Edje Electronics Main Github Repository Branch via this link: https://github.com/EdjeElectronics

## Tags
Use these tags to boost discoverability on GitHub and social platforms:
- `#FruitDetection`
- `#TensorFlowLite`
- `#ComputerVision`
- `#ObjectDetection`
- `#ReinforcementLearning`
- `#GoogleColab`
- `#MachineLearning`
- `#Python`
- `#OpenSource`
- `#TechnologyInnovation`

## License
[MIT License](LICENSE)

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for improvements.
