# PG_project
Falls occurs with high frequency in the older adults, children, and athletes It is a significant 
concern, particularly for the elderly and those with certain medical conditions, as they can lead 
to serious injuries or even death. It accounts for one of the most common and serious issues 
contributing to a disability, especially among elderly individuals. Among older adults, 
associated medical comorbidities correlate to an increased propensity to fall, and in turn, 
increased susceptibility to injury. 

The primary objective of ‘Fall detection using deep learning’ project is to develop an intelligent 
fall detection system using deep learning. The system will utilize the VGG16 model for feature 
extraction and classification, ensuring high accuracy in detecting falls from images or videos.

The expected outcome of this project is a robust and reliable model for fall detection system 
with high accuracy and minimal false alarms. By utilizing VGG16 and transfer learning, the 
model will be able to distinguish falls from normal activities effectively.


Key Features

**Binary image classification**: Detects and distinguishes between “Fall” and “Non-Fall” instances using image data.
**Transfer Learning with VGG-16**: Leveraged the power of pre-trained VGG-16 model (ImageNet weights) for effective feature extraction.
**Custom classifier**: Replaced top layers of VGG-16 with dense layers and softmax activation tailored for fall detection.
**High Accuracy**: Achieved 100% accuracy on test data with strong generalization and low loss, supported by precision, recall, F1-score, and confusion matrix.
**Model Evaluation**: Trained and tested on a balanced dataset (2000 images: 1000 fall, 1000 non-fall), with clear visualizations of performance metrics.
**Built with**: Python, TensorFlow, Keras, NumPy, OpenCV, Pandas, Matplotlib.


Tech Stack

**Language**: Python
**Frameworks/Libraries**: TensorFlow, Keras, NumPy, Pandas, Matplotlib, PIL, Scikit-learn
**Tools**: Jupyter Notebook, Graphviz, Pydot


Dataset

* Public dataset with **2000 images** (balanced: fall and non-fall).
* Images resized to **128x128**, RGB format.
* One-hot encoding used for binary labels.
* [Dataset Source](https://www.kaggle.com/datasets/vishnu6174/falldetectionclassification)



Future Enhancements

* Integrate **LSTM for motion detection** in video sequences.
* Deploy on **edge devices** (e.g., Raspberry Pi, Jetson Nano) for real-time monitoring.
* Expand dataset using **GANs or simulation** tools to improve model robustness.
* Add **pose estimation and context-awareness** using tools like OpenPose or MediaPipe.



Project Outcome

A robust fall detection model ready for deployment in healthcare and surveillance environments. By leveraging deep learning and transfer learning, the system can proactively assist in preventing injury and improving emergency response times.
