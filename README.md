# Sign Language Detection using Deep Learning

![Sign Language Detection](https://your-image-link-here.com)

## 📝 Project Overview
This project is a **real-time sign language detection system** that translates hand gestures into text and speech. Using **Computer Vision, Deep Learning, and Text-to-Speech (TTS)**, it enables communication for individuals who rely on sign language.

## 🚀 Features
- **Real-time hand gesture recognition** using OpenCV & MediaPipe.
- **Deep Learning-based classification** for 26 ASL (American Sign Language) letters.
- **Text-to-Speech conversion** to vocalize detected words.
- **User interaction controls** to build words dynamically.
- **High accuracy (~95%)** achieved through advanced training techniques.

## 📂 Dataset
The dataset consists of **hand keypoints extracted from images**. Due to file size limitations, the CSV files are hosted externally.

🔗 **Download CSV Files:**
1. [Hand Keypoint Cleaned CSV](https://your-google-drive-link.com)
2. [Uncleaned Hand Keypoint CSV](https://your-google-drive-link.com)

## 🏗️ Tech Stack
- **Python**
- **TensorFlow & Keras** (Deep Learning)
- **OpenCV & MediaPipe** (Computer Vision)
- **NumPy, Pandas, Matplotlib** (Data Processing & Visualization)
- **pyttsx3** (Text-to-Speech)

## 📥 Installation
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/PIYUSH-BAMNIA-25/Sign-Language-Translator.git
cd Sign-Language-Translator
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Download CSV Files
Place the CSV files in the **`data/`** folder after downloading from the links above.

## 🎯 Usage
Run the sign language detection script:
```sh
python sign_language_detection.py
```

### ✋ Controls:
- **Press 'S'** → Store the detected letter to form words.
- **Press 'Q'** → Exit the application.

## 📊 Model Architecture
The deep learning model is built using **TensorFlow & Keras** with the following layers:
- **Input Layer:** Hand keypoints (x, y coordinates)
- **Hidden Layers:** Fully connected layers with LeakyReLU & Dropout
- **Output Layer:** Softmax for classification into 26 letters

## 🔥 Future Enhancements
✅ **Improve prediction stability** with temporal smoothing.
✅ **Enhance UI/UX** with a graphical interface.
✅ **Support multi-hand detection** for full sign language sentences.
✅ **Deploy as a Web App** using Flask or Streamlit.

## 🤝 Contributing
Contributions are welcome! Feel free to submit **pull requests** or open an **issue** for bug reports and feature requests.

## 📜 License
This project is licensed under the **MIT License**.

## 👨‍💻 Author
**Piyush Bamnia**  
📧 Email: piyushbamnia25@gmail.com  
🔗 [GitHub](https://github.com/PIYUSH-BAMNIA-25) | [LinkedIn](https://www.linkedin.com/in/your-profile)

---

_If you like this project, don't forget to ⭐ the repository!_ 🌟
