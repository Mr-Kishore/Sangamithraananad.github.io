---
title: "AI-Enabled IoT Solar Tracker"
link: ""
image: "/img/solar-tracker-logo.png"
description: "Smart energy optimization system using AI and IoT for real-time solar fault detection and power forecasting."
featured: true
tags: ["AI", "IoT", "CNN", "LSTM", "Python", "WebApp"]
fact: "Optimizes solar energy by intelligently predicting faults and power output."
weight: 105
sitemap: 
    priority: 0.8
---

**AI-Enabled IoT Solar Tracker** is a smart, open-source solution developed to optimize solar panel efficiency by integrating real-time IoT data with powerful AI models. It predicts faults, forecasts power output, and helps maximize energy generation through intelligent solar tracking.

Unlike traditional systems that only collect data passively, our project actively learns from historical and real-time data to diagnose issues and predict trends—making solar setups smarter and more resilient.

### System Highlights

- Detects solar panel faults such as **Open Circuit**, **Short Circuit**, and **Partial Shading** using a **Convolutional Neural Network (CNN)**.
- Predicts future **power output** using **Long Short-Term Memory (LSTM)** models trained on time-series data.
- Provides a **user-friendly web interface** for uploading sensor data, visualizing forecasts, and viewing detected faults in tabular form.
- Includes live tracking metrics like **Voltage, Current, Power, Temperature, Humidity, Sunlight Intensity, and Panel Angle**.

### Technologies Used

- **IoT Integration**: Real-time solar data collected via sensors and fed to backend models.
- **Machine Learning**:
  - **CNN**: Used for multi-class fault detection. Trained to classify Normal, Open Circuit, Partial Shading, and Short Circuit scenarios.
  - **LSTM**: Used for time-series forecasting of solar power generation.
- **Python + Flask**: Backend server for model deployment and API handling.
- **Web Application**: Built with HTML/CSS/JS for CSV upload and results visualization.
- **Model Training**:
  - CNN: Achieved up to **87.12% validation accuracy** over 270 epochs.
  - LSTM: Achieved high prediction accuracy even with limited training epochs (3–10).
- **Data Handling**: Supports structured data with features like voltage, current, temperature, etc., for real-time analysis.

### Implementation Workflow

1. Sensor data collected from solar panels.
2. Data uploaded via web app or API.
3. AI models analyze data:
   - CNN classifies fault type.
   - LSTM predicts future power output.
4. Results shown via:
   - Confusion matrix for model evaluation.
   - Power prediction graphs.
   - Fault detection tables.

### Deployment & Workflow Management

- Hosted using Python’s Flask for quick deployment.
- Future-ready for containerization (e.g., Docker) and integration into larger energy systems.
- Modular design allows easy scaling for additional fault types or more complex forecasting models.

By combining the capabilities of **IoT** and **AI**, this project demonstrates a significant leap toward **sustainable energy optimization**, ensuring higher efficiency and reliability of solar energy systems.

**Project Members**: Aravindhan L, Sangamithra AU, Tanushree K, Yuvashankaran S  
**Institute**: Dr. N. G. P. Institute of Technology, Coimbatore  
**Affiliation**: Anna University, Chennai

