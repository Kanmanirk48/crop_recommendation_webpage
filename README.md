#  AI-Based Crop Recommendation System

This project predicts the most suitable crop to grow based on environmental conditions like nitrogen, phosphorus, potassium, temperature, humidity, pH, and rainfall. It uses machine learning and a Flask-based web interface for easy user interaction.

---

## Features

- Machine learning model trained on 2200+ samples
- Takes real-time user input for soil and weather parameters
- Predicts the best crop using a trained classifier
- Clean and simple web UI with Flask
- Displays recommended crop instantly

---

##  Technologies Used

- Python
- Scikit-learn
- Pandas, NumPy
- Flask (Web Framework)
- HTML/CSS (Frontend)
- Pickle (Model serialization)

---

##  Model Details

- Trained on `Crop_recommendation.csv` dataset
- Used `LabelEncoder` to encode target crop labels
- Final model saved as:
  - `crop_model.pkl`
  - `label_encoder.pkl`

---

##  Folder Structure

```
├── app.py                   # Flask app to serve model
├── crop_model.pkl           # Trained machine learning model
├── label_encoder.pkl        # Encoded crop labels
├── templates/
│   └── index.html           # Frontend form
├── static/
│   └── style.css            # CSS (optional)
└── Crop_recommendation.csv  # Dataset used for training
```

---

## Screenshot

![App Preview](screenshot.png)

---

##  How to Run

```bash
git clone https://github.com/kanmanirk/crop-recommendation-app.git
cd crop-recommendation-app
pip install -r requirements.txt
python app.py
```

- Then open `http://127.0.0.1:5000/` in your browser.

---

##  Author

**Kanmani R K**  
[GitHub Profile](https://github.com/kanmanirk)

---

##  License

This project is free for educational use and open-source contributions.

