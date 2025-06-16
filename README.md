# AI Model Deployment via Kubernetes UI

## 🔧 Stack
- UI: Streamlit
- Backend: Python
- K8s: Minikube + kubectl + Python client

## 🚀 Features
- Select from 5 AI models
- Set CPU and memory resources
- Deploy/Stop pods
- Logs pod activity

## ✅ Run
1. `minikube start`
2. `streamlit run app.py`

## 📁 Notes
- Model images are dummy (replaceable with real ones)
- Logs are written to `pod_log.txt`
