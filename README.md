🥔 Potato Leaf Disease Prediction using CNN
This project aims to detect and classify diseases in potato leaves using Convolutional Neural Networks (CNN) in TensorFlow. The model helps in early identification of common potato leaf diseases, which can assist farmers and researchers in applying the right treatment at the right time.
📌Problem Statement
Potato plants are susceptible to various leaf diseases that can significantly impact crop yield. Manual inspection is time-consuming and error-prone. This project builds an AI-based image classification system to automate the process.

📂 Dataset
Source: PlantVillage Dataset
Categories:
1.Early Blight
2.Late Blight
3.Healthy
The dataset is split into training, validation, and testing sets.

🧠 Model Architecture
Developed using TensorFlow Keras Sequential API
Includes:
1.Data preprocessing and augmentation.
2.Multiple convolutional and max-pooling layers.
3.Dense layer with softmax for multiclass classification.

📈 Results
Test Accuracy: 97.43%
Test Loss: 0.1590
Sample predictions with confidence shown using matplotlib <img width="676" height="680" alt="image" src="https://github.com/user-attachments/assets/12d7a091-9e51-46d1-bbfb-a1b5e7ca8aad" />



▶️ How to Run
1.Clone the repository: git clone https://github.com/YOUR_USERNAME/potato-leaf-disease-prediction.git
2.Open the notebook: jupyter notebook potato_leaf_disorder_prediction.ipynb
3.Follow the notebook steps to train or test the model.


Sample Output <img width="1180" height="1232" alt="image" src="https://github.com/user-attachments/assets/474d5599-d053-4504-98a5-f7e07c7fb8a4" />




