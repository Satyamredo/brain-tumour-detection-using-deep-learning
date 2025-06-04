# Brain Tumor Detection Using Deep Learning
This project leverages deep learning techniques to detect brain tumors from MRI images. Utilizing Convolutional Neural Networks (CNNs), the model classifies MRI scans into tumor and non-tumor categories, aiming to assist in early diagnosis and treatment planning.


For ease of use, the project is also available on Google Colab:<br>
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KfLVsD7ABHS3dxWbxML8zzxlPcH4SHt-?usp=sharing)


# 🧠 Overview
Objective: Automate the detection of brain tumors in MRI images using deep learning.
Approach: Implement a CNN-based model trained on a labeled dataset of brain MRI scans.
Outcome: Achieved high accuracy in classifying images, demonstrating the model's potential in medical diagnostics.


📁 Project Structure
brain-tumour-detection-using-deep-learning/
├── Brain_Tumor_Detection_code.ipynb   # Jupyter Notebook with model training and evaluation
├── brain_tumor_detection code.py      # Python script version of the notebook
├── bestmodel.keras                    # Saved trained model
├── Images from MRI Dataset.png        # Sample images from the dataset
├── Brain-tumor-detection graphs.png   # Training and validation accuracy/loss graphs
├── tumor_onn_model.svg                # Model architecture visualization
└── README.md                          # Project documentation


📊 Dataset
The dataset comprises MRI images labeled as either containing a tumor or not. Each image is preprocessed to ensure consistency in size and format. The dataset is split into training and testing sets to evaluate the model's performance effectively.


🛠️ Installation and Setup

1. Clone the Repository
git clone https://github.com/Satyamredo/brain-tumour-detection-using-deep-learning.git
cd brain-tumour-detection-using-deep-learning

2. Create a Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Dependencies
Ensure you have Python 3.6 or higher installed. Then, install the required packages:
pip install -r requirements.txt


🚀 Usage
You can run the project either through the Jupyter Notebook or the Python script.

Option 1: Using Jupyter Notebook
1. Launch Jupyter Notebook
- jupyter notebook
2. Open and Run
- Open Brain_Tumor_Detection_code.ipynb and run the cells sequentially to train and evaluate the model.

Option 2: Using Python Script
1. Run the Script
- python brain_tumor_detection\ code.py


🧪 Model Evaluation
The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. Training and validation accuracy/loss graphs are provided in Brain-tumor-detection graphs.png to visualize the model's learning progress.


📈 Results
Accuracy: Achieved high accuracy in classifying MRI images.
Model Architecture: Visualized in tumor_onn_model.svg
Sample Images: Provided in Images from MRI Dataset.png


📄 License
This project is licensed under the MIT License. See the LICENSE file for details.


🙏 Acknowledgments
Inspired by various deep learning applications in medical imaging.
Special thanks to the contributors and the open-source community for their invaluable resources.