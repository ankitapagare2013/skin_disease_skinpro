Skin Pro - Advanced Skin Disease Detection
Skin Pro is an advanced tool designed to recognize and identify various skin diseases using cutting-edge image processing and machine learning techniques. The project leverages deep learning models and a robust web-based framework to provide accurate and efficient skin disease detection.

🎯 Objective
The primary aim of Skin Pro is to:

Develop a reliable solution for detecting skin diseases using images.
Aid individuals in diagnosing their skin conditions effectively.
Utilize state-of-the-art machine learning and image processing tools to achieve high accuracy.
🛠️ Technologies Used
The project integrates the following technologies:

Django: A high-level Python web framework for backend development.
OpenCV: An open-source library for image processing and computer vision.
PyTorch: A popular deep learning framework for building and training models.
Timm: A library offering pre-trained PyTorch models for transfer learning.
⚙️ Features
Image-Based Skin Disease Detection: Supports the identification of multiple skin conditions.
Pre-Trained Models: Utilizes models like SVC, Logistic Regression, Random Forest, KNN, Decision Tree, Gradient Boosting, and Naive Bayes.
Real-Time Predictions: Integrates OpenCV for efficient image processing.
Web-Based Interface: Built using Django for an intuitive and accessible user interface.
🚀 How to Download and Run the Project
Prerequisites
Python 3.8+
Steps to Set Up
Clone the Repository
git clone https://github.com/B14-Group5/B14-Projects.git
cd B14-Projects
Install Dependencies
pip install -r requirements.txt
Download the model file
Download the model file from here: Drive link
Paste this file inside the B14-Projects/sample/ directory
Run Migrations
cd sample
python manage.py migrate
Start the Development Server
python manage.py runserver
Visit http://127.0.0.1:8000 in your browser.
📈 Future Enhancements
Expanding Dataset: Adding more skin disease categories for enhanced detection capabilities.
Deployment: Hosting the web application on cloud platforms.
🤝 Contributions
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

📄 License
This project is licensed under the MIT License.
