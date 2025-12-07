# 🧠 Smart Sorting: Identifying Rotten Fruits & Vegetables

An AI-powered web application that detects whether fruits or vegetables are **healthy or rotten** using image classification and transfer learning.

---

## 📌 Project Details

**Team ID**: LTVIP2025TMID42087  
**Team Members**:
- Y. Hari Kishore Reddy – [LinkedIn](https://www.linkedin.com) | yeddulaharikishore2004@gmail.com  

---

## 🚀 Features

- Upload images of fruits or vegetables
- Get instant predictions (Healthy or Rotten)
- Displays confidence score
- Clean and mobile-friendly user interface
- Contact form and Thank You page

---

## 🧠 Technologies Used

- **Python + Flask** – Web backend
- **TensorFlow/Keras** – Model development (MobileNetV2)
- **HTML + Tailwind CSS** – Frontend design
- **Kaggle / Colab** – Model training with GPU

---

## 🗂 Dataset

28 total categories:
- 14 fruits/vegetables × 2 classes (Healthy, Rotten)
- Examples: Apple, Mango, Carrot, Tomato, etc.

Preprocessing:
- Resized to 224x224
- Normalized pixel values
- Data augmentation used during training

---

## 🏗 Project Structure

SmartSortingApp/
│
├── app.py # Flask app
├── fruit_disease_model.h5 # Trained model
├── requirements.txt
├── README.md
├── templates/
│ ├── frontpage.html
│ ├── about.html
│ ├── predict.html
│ ├── result.html
│ ├── contact.html
│ └── thankyou.html
└── static/
└── uploads/ # Uploaded images


---

## 💻 How to Run Locally

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt

2. **Start the server:
   python app.py

3. **Open in browser:
   http://127.0.0.1:5000


📈 Future Scope:

1.Mobile app integration (Android/iOS)

2.Real-time webcam detection

3.Cloud deployment (Heroku/AWS)

4.Detection of diseases and pest-infected produce
