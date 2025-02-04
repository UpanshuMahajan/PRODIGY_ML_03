📌 Overview
This project implements an SVM (Support Vector Machine) model to classify images of cats and dogs using image feature extraction techniques. The dataset consists of labeled images, and the model aims to distinguish between the two classes effectively.

📂 Dataset
The dataset consists of images of cats and dogs from the Kaggle Dogs vs. Cats dataset.
Each image is preprocessed and converted into features before classification.
🛠️ Methodology
Data Preprocessing:

Resized images to a fixed size.
Converted images to grayscale to reduce computational complexity.
Applied Histogram of Oriented Gradients (HOG) to extract key features.
Model Training:

Implemented an SVM (Support Vector Machine) classifier with optimized hyperparameters.
Used feature vectors obtained from HOG descriptors for classification.
Evaluation:

Measured accuracy using training and test datasets.
Analyzed confusion matrix and classification reports.
📌 Results
Training Accuracy: 99.5%
Testing Accuracy: 86.4%
The model performed well on training data but had scope for improvement in generalization.
💻 Installation & Setup
🔹 Prerequisites
Ensure you have Python installed (recommended: Python 3.10.6).

🔹 Install Required Libraries
pip install numpy pandas scikit-learn matplotlib seaborn

🔹 Clone the Repository
git clone https://github.com/UpanshuMahajan/SVM-Classification-of-Cats-and-Dogs.git
cd SVM-Classification-of-Cats-and-Dogs

🔹 Run the Jupyter Notebook
Open the SVM_MODEL.ipynb notebook and execute the cells step by step.


jupyter notebook SVM_MODEL.ipynb
📝 Future Improvements
✔️ Implement Convolutional Neural Networks (CNNs) for better feature extraction.
✔️ Experiment with different kernels and hyperparameters to improve SVM performance.
✔️ Apply data augmentation techniques to enhance generalization.

