# Interpretable Electricity Theft Detection (7-Day)  
**Models:** LSTM | Transformer Attention | Grad-CAM  

This repo implements theft detection on **7-day consumption windows** using deep learning models with interpretability.  
Built from our full notebook (`notebooks/theft_detection.ipynb`) and restructured for reproducibility.  

---

## 🚀 Results

- **LSTM (7-day, ROS)**  
  - Accuracy: **87.5%**  
  - Loss: **0.3895**  
  - F1 ≈ **0.75** @ threshold **0.6**  

- **Transformer (7-day, ROS)**  
  - Accuracy: **86%**  
  - Loss: **0.3932**  
  - F1 ≈ **0.75** @ threshold **0.5**  

### Grad-CAM Visualizations  
- **LSTM Example:**  
  ![LSTM Grad-CAM](reports/figures/lstm_gradcam_example.png)  

- **Transformer Example:**  
  ![Transformer Grad-CAM](reports/figures/transformer_gradcam_example.png)  

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
pip install -r requirements.txt
