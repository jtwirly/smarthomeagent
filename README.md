### **📘 Smart Home AI Agent - README**  

---

## **🔍 Overview**  
This project is a **Smart Home AI Agent** that leverages:  
✅ **OpenAI API** for **energy price analysis & automation**  
✅ **ComEd & Bayou APIs** for **real-time & historical electricity data**  
✅ **Gradio Web UI** for **easy user interaction**  
✅ **Vision Transformers (ViT)** for **home occupancy detection**  

---

## **📌 Features**
### **🏡 Smart Home Automation**
- Fetch **real-time energy prices** from **ComEd API**  
- Retrieve **historical energy bills** from **Bayou API**  
- Automate **HVAC settings** based on weather & pricing  
- Perform **real-time home occupancy detection** using **ViT**

### **🖼️ Vision AI (ViT)**
- Uses **Google's ViT model** to analyze images  
- Determines if a **home is occupied or empty**  
- Can be expanded for **security automation**  

### **🖥️ Web UI (Gradio)**
- Users can **ask for energy pricing, HVAC adjustments, or home occupancy**  
- Results are displayed in a **simple web-based chatbot**  

---

## **🛠️ Setup & Installation**
### **1️⃣ Install Dependencies**
Manually install:
```bash
pip install transformers gradio openai requests torch PIL
```

### **2️⃣ Set Up API Keys**
Edit `config.py` and add:
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
### **🌡️ Get Weather & Optimize HVAC**
```
User: "What is the weather like in Chicago?"
Bot: "The current high temperature is 78°F."
```
```
User: "Optimize HVAC settings based on energy prices."
Bot: "Energy price is high! Adjusting thermostat for efficiency."
```

### **⚡ Get Real-Time Energy Pricing**
```
User: "What is the current electricity price in Illinois?"
Bot: "The latest ComEd price is 14.2 cents/kWh."
```

### **🏡 Detect Home Occupancy**
```
User: "Is my home occupied?"
Bot: "Processing image... Occupancy status: Empty."
```

---

## **🎯 Future Enhancements**
✅ **Integrate with Smart Devices (e.g., Nest, Tesla Powerwall, Home Assistant API)**  
✅ **Enable Real-Time Image Processing from IP Cameras**  
✅ **Enhance AI Automation with Reinforcement Learning**  

---

## **📜 License**
This project is **MIT Licensed** – Feel free to modify & use. 🚀

---

🚀 **Built for a Smarter, Energy-Efficient Home!** 🚀
