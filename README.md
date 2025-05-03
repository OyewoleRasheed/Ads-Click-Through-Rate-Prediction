# Ads-Click-Through-Rate-Prediction

This project predicts whether a user will click on an online advertisement based on profile details like **daily internet usage**, **time spent on site**, **income**, **age**, and **gender**.
It features an interactive web interface built using **Gradio** for easy, no-code predictions.

---

## 🚀 Features

* Predict if a user will click on an ad.
* Simple and user-friendly **Gradio web interface**.
* Input fields:

  * Daily Time Spent on Site
  * Age
  * Area Income
  * Daily Internet Usage
  * Gender (Male/Female)

---

## 🛠 Requirements

Install dependencies using pip:

```bash
pip install numpy pandas scikit-learn gradio joblib
```

---

## 📂 Files

* `model.joblib` — Pre-trained machine learning model file.
* `app.py` — Python script to launch the Gradio app.
* `README.md` — Project description (this file).

---

## ▶️ How to Run

1. Install the required packages:

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install numpy pandas scikit-learn gradio joblib
```

2. Launch the app:

```bash
python app.py
```

3. The app will open in your browser automatically! 🎉

---

## 🌐 Usage Example

1. Enter user details:

   * Example: `Daily Time Spent on Site = 68.0`, `Age = 35`, `Area Income = 55000`, etc.
2. Click **Submit**.
3. See prediction: *"Will the user click on ad = 1"*
   (`1` = Yes, `0` = No)

---

## 📦 Model Details

* Trained using **scikit-learn**.

* Features used:

  * `Daily Time Spent on Site`
  * `Age`
  * `Area Income`
  * `Daily Internet Usage`
  * `Gender`

* Model saved with **joblib** for efficient loading.

---

## 🙌 Credits

* Original machine learning workflow inspired by [The Clever Programmer's tutorial](https://thecleverprogrammer.com/2023/01/16/ads-click-through-rate-prediction-using-python/).
* Gradio web interface and app adaptation by [Oyewole Rasheed](https://github.com/OyewoleRasheed).

---

## 📄 License

This project is open-source and free to use under the MIT License.

---

### ⭐️ Star this repo if you find it useful!

### 🛠 Created with ❤️ by [Oyewole Rasheed](https://github.com/OyewoleRasheed)

