# IBM Emotion Detector

An AI-powered web application that analyzes text to detect emotional nuances such as joy, sadness, anger, fear, and disgust. This project leverages the **IBM Watson NLP library** and is deployed using the **Flask** framework.

## 🚀 Features
- **Emotion Analysis:** Extracts specific emotional scores from any text input.
- **Dominant Emotion Detection:** Automatically identifies the strongest emotion in the provided text.
- **Web Interface:** User-friendly UI built with HTML/CSS and JavaScript.
- **Error Handling:** Robust processing for blank inputs and unexpected system errors.

## 🛠️ Tech Stack
- **Backend:** Python, Flask
- **AI/NLP:** IBM Watson Natural Language Processing library
- **Testing:** Unit testing with Python's `unittest`
- **Development:** VS Code

## 📋 Prerequisites
Before running the application, ensure you have the following installed:
- Python 3.x
- Flask (`pip install flask`)
- IBM Watson NLP library

## 🔧 Installation
1. **Clone the repository:**
```bash
git clone https://github.com
cd emotion-detector
```

2. **Install dependencies:**
```bash
git clone https://github.com/aiedwardyi/ibm-project-emotion-detector
cd emotion-detector
```

3. **Run the application:**
```bash
python3 server.py
```

The app will typically run on http://localhost:5000/. 

### 📖 Usage
Open your browser and navigate to the local host URL.
Enter the text you wish to analyze in the text field (e.g., "I am so excited about this project!").
Click the "Run Emotion Analysis" button.
View the results, which include scores for various emotions and the identified dominant emotion. 

### 📁 Project Structure
```tree
emotion-detector/
├── EmotionDetection/        # Package for emotion detection logic
│   ├── __init__.py
│   └── emotion_detection.py # Module interacting with Watson NLP
├── static/                  # CSS and JS files
├── templates/               # HTML templates (index.html)
├── server.py                # Flask server entry point
├── test_emotion_detection.py# Unit tests
└── requirements.txt         # Project dependencies
```

### 🤝 Credits
Developed as part of the IBM AI Development certification.