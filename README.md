### **📘 Smart Home AI Agent - README**  

---

## **🔍 Overview**  
This project was created for the final project of MIT's Hands-on Deep Learning class. It is a **Smart Home AI Agent** that leverages:  
✅ **OpenAI API** for **energy price analysis & automation**  
✅ **ComEd & Bayou APIs** for **real-time & historical electricity data**  
✅ Neural Networks (DNN) for future energy demand prediction 

✅ **Gradio Web UI** for **easy user interaction**  

---

## **📌 Features**
### **🏡 Smart Home Automation**
- Fetch **real-time energy prices** from **ComEd API**  
- Retrieve **historical energy bills** from **Bayou API**
- Predicts energy demand using a trained Neural Network (DNN)
- Automates HVAC settings based on AI-powered forecasts

### **🖥️ Web UI (Gradio)**
- Users can **ask for energy pricing, HVAC adjustments, or home occupancy**  
- Results are displayed in a **simple web-based chatbot**  

---

## **🛠️ Setup & Installation**
Smart_Home_Agent_8.ipynb has neural network integration

### **1️⃣ Install Dependencies**
Manually install:
```bash
pip install transformers gradio openai requests torch tensorflow keras PIL
```

### **2️⃣ Set Up API Keys**
```python
OPENAI_API_KEY = "your-api-key"
COMED_API_URL = "https://hourlypricing.comed.com/api?type=5minutefeed&format=json"
BAYOU_API_KEY = "your-bayou-api-key"
```

### **3️⃣ Run the Gradio Web UI**
```bash
python gradio_ui.py
```
Then open **`http://localhost:7860`** in your browser.

---

## **🚀 Usage**
### **🌡️ Get Weather**
```
User: "What is the weather like in Chicago?"
Bot: "The current high temperature is 78°F."
```

### **⚡ Get Real-Time Energy Pricing**
```
User: "What is the current electricity price in Illinois?"
Bot: "The latest ComEd price is 14.2 cents/kWh."
```

### 🌡️ Predict Future Energy Demand 
```
User: "How much electricity will I use over the next 6 hours?"
Bot: "Based on your past usage, your predicted energy consumption for the next 6 hours is 1.8 kWh."
```

### Optimize HVAC 
```
User: "Optimize HVAC settings based on energy prices."
Bot: "Energy price is high! Adjusting thermostat for efficiency."
```
```
User: "Optimize HVAC settings based on predicted demand."
Bot: "Energy usage is expected to be high. Adjusting thermostat to 70°F for efficiency."
```

### **⚡ Get Real-Time Energy Pricing**
```
User: "What is the current electricity price in Illinois?"
Bot: "The latest ComEd price is 14.2 cents/kWh."
```

---

## **🎯 Future Enhancements**
✅ **Integrate with Smart Devices (e.g., Nest, Tesla Powerwall, Home Assistant API)**  
✅ **Enable Real-Time Image Processing from IP Cameras**  
✅ **Enhance AI Automation with Reinforcement Learning**  
✅ **Vision Transformers (ViT)** for **home occupancy detection**  
- Perform **real-time home occupancy detection** using **ViT**
- Uses **Google's ViT model** to analyze images  
- Determines if a **home is occupied or empty**  
- Can be expanded for **security automation**  

---
## 👥 Collaborators

Jennifer Turliuk, Siddharth Chilukuri, Dominic Sudnik, Kike Vera

---
## 📜 License
This project is **MIT Licensed** – Feel free to modify & use. 🚀

---

🚀 **Built for a Smarter, Energy-Efficient Home!** 🚀

---
## Sample Uses

<img width="1242" alt="Screen Shot 2025-03-13 at 9 30 55 PM" src="https://github.com/user-attachments/assets/58eec9a0-fc54-4d51-9c26-3dd6bc9870c3" />
<img width="1250" alt="Screen Shot 2025-03-13 at 9 30 26 PM" src="https://github.com/user-attachments/assets/d04350ea-a71d-410f-8fc2-076f77f6652e" />
<img width="1257" alt="Screen Shot 2025-03-13 at 9 29 30 PM" src="https://github.com/user-attachments/assets/9f8a79f4-6f41-48c3-b9e4-1d12f707f547" />
<img width="1242" alt="Screen Shot 2025-03-13 at 9 28 34 PM" src="https://github.com/user-attachments/assets/b8b8fadd-c693-4434-a806-9303f8ccdedf" />
<img width="1244" alt="Screen Shot 2025-03-13 at 9 27 11 PM" src="https://github.com/user-attachments/assets/a676fa17-4050-469c-b6e2-4edcabc67a56" />
<img width="1248" alt="Screen Shot 2025-03-13 at 9 25 45 PM" src="https://github.com/user-attachments/assets/21b4778e-03e4-4ff3-9199-ef1758de2227" />
<img width="1237" alt="Screen Shot 2025-03-13 at 9 04 01 PM" src="https://github.com/user-attachments/assets/0cd4c501-7018-4f39-8371-2a5dafbd3306" />
<img width="1258" alt="Screen Shot 2025-03-13 at 9 03 43 PM" src="https://github.com/user-attachments/assets/23f66a20-dd2b-4ae7-b9db-ca78016e62d2" />
<img width="1246" alt="Screen Shot 2025-03-13 at 9 03 01 PM" src="https://github.com/user-attachments/assets/957098bf-8487-4478-af95-c267b2d16e0c" />
<img width="1239" alt="Screen Shot 2025-03-13 at 9 02 17 PM" src="https://github.com/user-attachments/assets/95a12e05-4056-42de-a9f4-b736ad9125e0" />
<img width="1253" alt="Screen Shot 2025-03-13 at 9 01 47 PM" src="https://github.com/user-attachments/assets/7e775f23-2a25-4f8c-b843-f61b20039463" />

