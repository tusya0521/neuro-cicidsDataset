# NeuroIDS Dataset

The **NeuroIDS Dataset** is a curated collection of flow-level network traffic records created for research and development in **Intrusion Detection Systems (IDS)** using **deep learning**. It is optimized for hybrid architectures like **CNN**, enabling both spatial and temporal feature learning.

## 📖 Description
- Contains **normal and malicious** traffic flows.  
- Includes multiple attack categories: DoS, brute-force, infiltration, botnet, and port scans.  
- Flow-level features: IPs, ports, protocols, packet/byte counts, timestamps, session durations.  
- Designed for compactness, efficiency, and real-world applicability.  

## 🚀 Applications
- Intrusion Detection (IDS/IPS) research  
- Network anomaly detection  
- AI-driven cybersecurity benchmarking  
- Comparative evaluation against datasets like CICIDS2017  

## 📊 Model Performance (Neuroids IDS)

Our deep learning model (CNN) achieved the following results on the Neuroids dataset:

- **Training Accuracy:** 99.46%  
- **Training Loss:** 0.0746  
- **Validation Accuracy:** 99.72%  
- **Validation Loss:** 0.0624  

These results demonstrate the robustness of the model in detecting network intrusions with very low error rates.

### Training
The CICIDS2017 dataset was collected by the Canadian Institute for Cybersecurity (CIC) to simulate real-world network traffic for intrusion detection research. It was generated in a controlled testbed environment that included routers, switches, servers, and client machines running common applications such as browsing, streaming, email, and chat. Both benign traffic and a wide variety of attack scenarios (DDoS, Brute Force, Heartbleed, Botnet, Web attacks, Infiltration, etc.) were executed over multiple days. Network flow features were extracted using CICFlowMeter, resulting in a comprehensive labeled dataset suitable for training and evaluating intrusion detection systems.
The main training code can be found in the train.py file that showcases the main CNN or the Neural Network that works as the main Brain of the system doing the required tasks.
