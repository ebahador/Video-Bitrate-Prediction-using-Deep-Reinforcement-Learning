Video Streaming Quality Optimization Project
Concordia University - Fall 2023
Artificial Intelligence for Networked Multimedia Systems
COMP 691

Supervisor:

Dr. Abdelhak Bentaleb
Assistant Professor
Email: abdelhak.bentaleb@concordia.ca

Author:

Amir Bahador Eizadkhah
Master of Applied Computer Science
Email: eizadkhah.bit@gmail.com
______________________________________________________________________________________________________________
Project Overview:

This project, intended for the final project of COMP 691, utilizes machine learning models like LSTM, Random Forest, SVM, and XGBoost to predict video quality and optimize streaming. It focuses on improving the Quality of Experience (QoE) while using lower bitrates and includes a bitrate ladder for adaptive streaming.
______________________________________________________________________________________________________________
Main Components:

1. Data Preprocessing
2. Supervised Learning and LSTM
3. Overall Results
4. Adaptive Bitrate Streaming with Q-Learning
______________________________________________________________________________________________________________
Dataset:

The project uses a dataset of 600 1080p videos encoded at various resolutions and bitrates, available at: Kaggle Dataset
______________________________________________________________________________________________________________
Running the Code:

Prerequisites:

Google Colab environment or Visual Studio Code (VSCode) recommended for running the code because the code is in Jupyter Notebook.

Instructions:

If Using Pre-trained Models and Pre-encoded Values:

1. Skip Sections: 1.2, 1.3.9, 4.9.0, 2.2.3 (Plotting part).
2. Path Replacement: In sections 1.3.10, 2.1, and 4.9.1, replace the path with your path.
3. Continue Running: Proceed with executing the remaining code.

If Not Using Pre-trained Models:

1. Dataset Path: Copy your dataset path into the video_directory variable.
2. Encoding Setup: Continue running the code until 1.3.9. Replace encoded_folder path with your path (where encoded videos will be stored) and un_encoded_folder path with the original dataset path. Ensure all datasets are in mp4 format. Update all paths in this section for storing encoded features.
3. Feature Loading: Skip 1.3.10 but replace paths for future feature loading.
4. Model Training: Run the code until 2.1, updating paths for saving ML models.
5. Final Steps: Continue to sections 4.9.0 and 4.9.1, replacing paths as needed.
______________________________________________________________________________________________________________
Additional Information:

For detailed implementation notes, refer to the comments within the code.
This project aims to explore video streaming quality for COMP 691.