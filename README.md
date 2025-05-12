🏥 Disease Prediction System

Welcome to the **Disease Prediction System!** This is a *Streamlit-based web application* that provides **AI-driven predictions** for Diabetes, Heart Disease, and Parkinson's Disease based on user inputs. 🚀


📌 Features
✅ User-friendly UI built with Streamlit  
✅ Three disease predictions (Diabetes, Heart Disease, Parkinson's Disease)  
✅ Interactive input fields for entering health parameters  
✅ AI-powered predictions using pre-trained models  
✅ Error handling for missing models or incorrect inputs  

---

 🖥️ Tech Stack
- Python 🐍  
- Streamlit 🎨  
- Machine Learning (Pickle Models) 🤖  

---

📂 Project Structure

```
📦 Disease-Prediction-System
├── models/
│   ├── diabetes-prediction.sav
│   ├── heart-disease-prediction-model.sav
│   ├── parkinsons_model.sav
├── app.py
├── requirements.txt
├── README.md
```

---

🚀 Installation & Setup
1. Clone the repository📥  
   ```bash
   git clone https://github.com/yourusername/disease-prediction.git
   cd disease-prediction
   ```

2. Install dependencies📦  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application 🏃‍♂️  
   ```bash
   streamlit run app.py
   ```

📊 Usage Guide
1. Open the web interface.  
2. Select a disease category from the *sidebar menu*:  
   - 🩸 Diabetes Prediction  
   - ❤️ Heart Disease Prediction  
   - 🧠 Parkinson's Disease Prediction  
3. Enter the required parameters.  
4. Click the test button to get predictions! 🎯  

---

🎯 Prediction Models
🔹 Diabetes Model  
   - Inputs: Pregnancies, Glucose, Blood Pressure, BMI, Insulin, etc.  
   - Prediction: *Diabetes Positive* 🔴 / *Diabetes Negative* 🟢  

🔹 Heart Disease Model  
   - Inputs: Age, Cholesterol, Max Heart Rate, Blood Pressure, etc.  
   - Prediction: *Heart Disease Detected* 🔴 / *No Heart Disease* 🟢  

🔹 Parkinson’s Disease Model
   - Inputs: Various voice-related parameters (Jitter, Shimmer, HNR, etc.)  
   - Prediction: *Parkinson’s Detected* 🔴 / *No Parkinson’s* 🟢  

🤝 Contributing
Feel free to contribute! 🔥 If you find bugs or want to add new features, create a pull request.

🛠️ Troubleshooting
If you face issues:  
- Ensure you have all required dependencies installed ✅  
- Check if model files are available in the `models/` directory 🗂️  
- Verify Streamlit is installed and up-to-date 🚀
  
📜 License
This project is licensed under the MIT License

Demo Link:https://disease-prediction-ufzbnaxcphzwspex25czlm.streamlit.app/
