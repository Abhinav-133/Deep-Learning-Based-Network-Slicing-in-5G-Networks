# Deep-Learning-Based-Network-Slicing-in-5G-Networks
<img width="606" height="357" alt="fig1" src="https://github.com/user-attachments/assets/c5914d0b-f57f-481f-b6b5-fac3309800f4" />(fig1)

## 📌 Introduction
**Network slicing in 5G** is the process of dividing a single physical network infrastructure into multiple **virtual networks (slices)**.  
Each slice is tailored to meet the requirements of specific applications, services, or user groups. This ensures **customized performance** while sharing the same physical backbone.

<img width="732" height="406" alt="fig2" src="https://github.com/user-attachments/assets/bc297d98-da72-473e-a2ec-5d6caef3bda9" />(fig2)

---

## 🎯 Objectives
The research is driven by the following goals:

- **Resource Optimization** → Apply deep learning models to improve slice-level resource allocation.  
- **Adaptive Slice Management** → Use AI to dynamically manage slices based on traffic and service requirements.  
- **QoS Improvement** → Anticipate congestion and latency issues to maintain quality of service.  
- **Scalability** → Support flexible scaling of slices with minimal overhead and without impacting reliability.  

---

## 🏗️ Architecture
The proposed slicing framework integrates **physical** and **virtual layers**:

1. **Physical Layer** → Base stations, routers, and servers.  
2. **Virtualization Layer** → Abstracts hardware into virtual units using **SDN** (Software-Defined Networking) and **NFV** (Network Function Virtualization).  
3. **Orchestration & Management Layer** → Responsible for slice lifecycle (creation, scaling, termination).  

---

## Workflow  

1. **Setup & Architecture**  
   - SDN/NFV principles used to design the slicing framework.  

2. **Data Handling**  
   - Cleaning and encoding the dataset  
   - Feature extraction (e.g., Cramer’s V)  
   - Filling missing values  

  <img width="669" height="434" alt="fig3" src="https://github.com/user-attachments/assets/668bd1a3-19d9-4192-b46b-14932a573a8c" />(fig1)

3. **Exploratory Analysis**  
   - Visualized features and traffic patterns  
   - Checked importance using ML techniques  


3. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions  
   - Categorized features  
   - Extracted feature importance
   <img width="900" height="293" alt="fig4" src="https://github.com/user-attachments/assets/5bfcd6a7-7f01-46fb-a195-78c9be89ede5" />(fig4)


 
4. **Model Training & Evaluation**  
   - Supervised deep learning architectures tested with multiple activation functions  
   - Metrics: **Accuracy, Precision, Recall, F1 Score**  
   - Performance compared across different setups 

---

## 📊 Results
- **Performance Metrics**: Higher throughput, reduced latency, and improved reliability.  
- **Evaluation**: Confusion matrices & classification reports validated model efficiency.  
- **Comparative Analysis**: Deep learning consistently outperformed traditional approaches.  

<img width="746" height="461" alt="results" src="https://github.com/user-attachments/assets/d6f7873f-ee1e-4ed7-998b-260e4e5df1ed" />(fig5)

---

## ⚙️ Implementation Details
- **Data Preparation** → Dataset cleaned, normalized, and encoded.  
- **Feature Selection** → Significant attributes identified using **Random Forest** & **Cramer’s V**.  
- **Model Training** → Supervised DL models optimized for slice classification and prediction.  
- **Evaluation** → Benchmarked vs. conventional ML methods to demonstrate improvements.  

---

## 🚀 Future Scope
- Develop a **5G simulation environment** for real-world testing.  
- Automate **KPI extraction** from network devices.  
- Explore **hybrid AI models** combining ML + DL techniques.  
- Extend framework adaptability for **next-gen 6G networks**.  

---

