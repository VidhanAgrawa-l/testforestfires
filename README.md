# **🔥 Forest Fire Prediction using Machine Learning**

### **📌 Overview**
This project leverages **machine learning** to predict forest fire risks based on key **environmental factors** and **fire weather indices**. By analyzing temperature, humidity, wind speed, and specialized fire indices, the model provides **actionable insights** to assist in fire prevention, risk assessment, and resource allocation.

---

## **📊 Dataset: Algerian Forest Fires**
- Source: **Collected from Bejaia (Northeast) and Sidi Bel-Abbes (Northwest), Algeria**
- Time Period: **June to September 2012**
- **244 total instances** (122 per region)
- **11 input attributes + 1 output attribute (Fire/No Fire classification)**
- **138 instances** classified as fire 🔥
- **106 instances** classified as no fire 🌿

---

## **🌿 Environmental Factors Considered**
- **Temperature (°C):** Higher temperatures dry fuels faster, increasing fire risks.
- **Humidity (%):** Lower humidity means drier vegetation, making fires more likely.
- **Wind Speed (km/h):** Strong winds provide oxygen and spread flames rapidly.
- **Rain (mm):** Precipitation increases moisture content, reducing fire probability.

---

## **🔥 Fire Weather Indices Used**
These indices help in quantifying fire danger:
- **FFMC (Fine Fuel Moisture Code):** Measures dryness of surface fuels. High values (>90) indicate highly flammable conditions.
- **DMC (Duff Moisture Code):** Represents moisture in moderate-depth organic layers.
- **DC (Drought Code):** Reflects long-term dryness and deep soil moisture levels.
- **ISI (Initial Spread Index):** Predicts how fast a fire will spread.
- **BUI (Buildup Index):** Indicates total fuel available for combustion.
- **FWI (Fire Weather Index):** Overall fire risk score combining all indices.

---

## **📌 Model & Approach**
- **Preprocessing:** Data cleaning, feature engineering, and scaling.
- **Model Selection:** Experimented with multiple ML models (Logistic Regression, Random Forest, SVM, etc.).
- **Evaluation Metrics:** Accuracy, Precision, Recall, and F1-score.
- **Deployment:** API created using **FastAPI** for easy integration.

---

## **🚀 How to Run the Project**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/VidhanAgrawa-l/testforestfires
cd forestfire-main
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Model**
```bash
python application.py 
```

---

## **📌 Results & Insights**
- Model achieves **high accuracy** in predicting fire occurrence.
- **Key Influencers:** Temperature, Humidity, Wind Speed, and FFMC.
- Fire Weather Indices improve prediction reliability.

---

## **💡 Future Improvements**
- Integrate **real-time weather data** for live predictions.
- Optimize model for **better generalization across regions**.
- Develop a **web dashboard** for easy data visualization.

---

## **👨‍💻 Contributors**
- **Core Developer & ML Enginee** - VIDHAN AGRAWAL
- **INSTRUCTOR** - KRISH NAIK

---

## **🔗 Connect with Me**
- **LinkedIn:** [Your Profile](https://www.linkedin.com/in/vidhan-agrawal-7133242a2/)
- **GitHub:** [Your GitHub](https://github.com/VidhanAgrawa-l)

🚀 **Let's make AI-driven fire prevention a reality!**

