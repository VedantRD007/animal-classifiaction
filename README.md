# 🐾 Animal Image Classification

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Gradio](https://img.shields.io/badge/Gradio-Web%20Interface-green)

## 📌 Project Overview
This project is an **animal image classifier** built using **TensorFlow/Keras**. It predicts the species of an animal based on input images. The model is deployed using **Gradio** for easy interaction.

## 🚀 Features
✅ Uses **CNN (Convolutional Neural Networks)** for image classification.  
✅ Trained on a dataset of various animal species.  
✅ Provides a web-based interface via **Gradio**.  
✅ Supports real-time image classification.  
✅ Easy deployment on cloud platforms.  

## 📂 Repository Structure
```
Animal-Classification-Repo/
│-- data/              # Dataset (place dataset files here)
│-- models/            # Trained models stored here
│-- animal_classifier.py   # Model training and evaluation script
│-- gradio.ipynb             # Gradio interface for deployment
│-- requirements.txt   # Dependencies
│-- README.md          # Project documentation
```

## 📥 Installation
To run this project, clone the repository and install dependencies:
```sh
git clone <https://github.com/VedantRD007/animal-classifiaction.git>
cd Animal-Classification-Repo
pip install -r requirements.txt
```

## 🏋️ Training the Model
To train the model on your dataset, run:
```sh
python animal_classifier.ipynb
```

## 🎨 Running the Gradio App
To launch the web interface for classification:
```sh
python gradio.ipynb
```

## 📌 Example Prediction
**Input Image:**
![Sample Input](screenshots/sample_input.jpg)


## 🔗 Dependencies
Ensure you have the following installed (listed in `requirements.txt`):
```
tensorflow
keras
numpy
pandas
matplotlib
seaborn
gradi
opencv-python
```
## ☁️ Deployment
This model can be deployed on platforms like:
- **Hugging Face Spaces** (Gradio-based deployment)
- **Heroku** (Flask/Gradio-based API)
- **AWS Lambda** (Serverless execution)

## 🤝 Contributing
Feel free to submit pull requests for improvements! Contributions are always welcome.