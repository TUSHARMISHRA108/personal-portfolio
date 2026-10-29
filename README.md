# personal-portfolio
Personal portfolio website hosted on AWS (S3 + CloudFront) featuring an interactive XGBoost ML hyperparameter sandbox inspired by my IIT Kharagpur ML Hackathon performance.
# Personal Portfolio Website — Tushar Kumar Mishra

A personal portfolio website built and deployed on AWS as part of the AWS Portfolio Hackathon. It highlights my academic journey at IIT Jodhpur, core AI/ML skills, projects, and competitive hackathon achievements.

🌐 **Live Website:** (https://d1k0hgf08zuzm.cloudfront.net)  
👨‍💻 **GitHub Repository:** (https://d1k0hgf08zuzm.cloudfront.net)

---

## 🚀 Key Features

- **About Me & Narrative:** Highlights my background in Applied AI & Data Science at IIT Jodhpur (CGPA: 7.09).
- **Skills & Superpowers:** Data Science, Machine Learning, Computer Vision, RAG, and Deployment tools.
- **Projects Highlighted:**
  - *KrishiMitra AI* — Multimodal Agricultural Assistant (Gemini, Groq, Bhashini, RAG).
  - *Decentralized Water Exchange Platform (DWEP)* — Real-Time IoT Stream Analytics.
  - *Smart Agri-Tech Processing (Dal Dilemma)* — Process Optimization using Machine Learning Regression.
- **🎯 Creative Interactive Feature:** **XGBoost RMSE Hyperparameter Sandbox**
  - Visitors can tweak Learning Rate ($\eta$), Max Depth ($d$), and Estimator count in real time to simulate model training and attempt to beat/match my benchmark score from ranking 60th out of ~500 teams at the IIT Kharagpur ML Hackathon.

---

## ☁️ AWS Architecture

- **AWS S3:** Serves as the static object store for website assets (`index.html`).
- **Amazon CloudFront:** Functions as the global Content Delivery Network (CDN) with automatic HTTP-to-HTTPS redirection and custom caching policies.
- **AWS OAC (Origin Access Control):** Restricts direct public S3 bucket access, ensuring traffic flows securely through CloudFront.

---

## 🛠️ Local Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/TUSHARMISHRA108/personal-portfolio.git](https://github.com/YOUR_USERNAME/personal-portfolio.git)
