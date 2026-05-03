# HARVESTIFY---Crop-Recommendation-System
AI-powered crop recommendation system using Machine Learning and Deep Learning to suggest optimal crops, fertilizers, and detect plant diseases from leaf images.

HARVESTIFY – Smart Crop Recommendation System
🚀 AI-powered Agriculture Assistant using Machine Learning & Deep Learning

HARVESTIFY is a web-based intelligent system that helps farmers and agricultural enthusiasts make better decisions by recommending:

🌱 Best crops to grow
🌾 Suitable fertilizers
🍃 Plant disease detection & solutions
💡 Motivation

Agriculture plays a crucial role in India’s economy. However, farmers often face challenges like:

Lack of soil knowledge
Improper fertilizer usage
Crop diseases

HARVESTIFY leverages Machine Learning and Deep Learning techniques to provide smart, data-driven agricultural recommendations.

✨ Features
🌱 Crop Recommendation
Input: Soil nutrients (N, P, K), temperature, humidity, pH, rainfall
Output: Best crop to grow
🌾 Fertilizer Recommendation
Input: Soil composition + crop type
Output: Suggested fertilizers & nutrient corrections
🍃 Plant Disease Detection
Input: Leaf image
Output:
Disease name
Cause
Prevention methods
📊 Datasets Used
Crop Recommendation Dataset (Kaggle)
Fertilizer Dataset (CSV format)
Plant Disease Dataset (PlantVillage)
🛠️ Tech Stack
💻 Frontend
HTML
CSS
JavaScript
Bootstrap
⚙️ Backend
Python
Flask
🤖 Machine Learning / Deep Learning
NumPy
Pandas
Scikit-learn
TensorFlow / PyTorch
🔧 Tools
Git & GitHub
Jupyter Notebook
Heroku (Deployment)
🌐 Deployment
Hosted on Heroku
Accessible via web browser
📸 Demo
Crop Recommendation

Fertilizer Suggestion

Disease Detection

🧑‍💻 How to Run Locally
🔹 Prerequisites

Steps
# Clone repository
git clone -b deploy https://github.com/Gladiator07/Harvestify.git

# Navigate to project folder
cd Harvestify

# Create environment
conda create -n harvestify python=3.6.12
conda activate harvestify

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py

Open in browser:

http://127.0.0.1:5000/
Supported Crops (Disease Detection)
Apple
Tomato
Potato
Corn
Grape
Strawberry
Peach
Orange
Soybean
Pepper
Blueberry
🔍 How It Works
User inputs soil data or uploads plant image
Backend processes data using ML/DL models
Model predicts:
Crop
Fertilizer recommendation
Disease detection
Results are displayed through the web interface
📈 Future Improvements
Improve UI/UX design
Use real-time agricultural datasets
Integrate live weather APIs
Build mobile application
Optimize model performance
🤝 Contributing
Fork the repository
Create a new branch
Make your changes
Submit a pull request
Git
Python (3.6+)
Anaconda / Miniconda (recommended)
