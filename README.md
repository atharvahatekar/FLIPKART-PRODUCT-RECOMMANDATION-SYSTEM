# Flipkart Product Recommendation System

![Demo](static/demo.gif)

## 🚀 Overview

The **Flipkart Product Recommendation System** is a robust, end-to-end solution designed to deliver personalized product recommendations using real-world e-commerce data. Built with modern LLMOPS practices, this project demonstrates scalable data ingestion, processing, and deployment using Flask, Docker, and cloud-native tools like Prometheus and Grafana for monitoring. 

> **Why is this project in demand?**
>
> - E-commerce recommendation systems are at the core of online retail giants like Amazon, Flipkart, and Walmart.
> - Companies are actively seeking engineers who can build, deploy, and monitor intelligent recommendation engines at scale.
> - This project showcases not just ML, but also production-grade deployment, observability, and best practices in Python development.

---

## 🗂️ Project Structure

```
FLIPKART-PRODUCT-RECOMMENDATION-SYSTEM/
│
├── app.py                        # Flask application entry point
├── Dockerfile                    # Containerization for deployment
├── flask-deployment.yaml         # Kubernetes deployment for Flask app
├── requirements.txt              # Python dependencies
├── setup.py                      # Project setup
│
├── data/
│   └── flipkart_product_review.csv   # Raw product review data
│
├── flipkart/
│   ├── __init__.py
│   ├── config.py                 # Configuration management
│   ├── data_converter.py         # Data preprocessing utilities
│   ├── data_ingestion.py         # Data ingestion pipeline
│   └── rag_chain.py              # Retrieval-Augmented Generation (RAG) logic
│
├── utils/
│   ├── __init__.py
│   ├── custom_exception.py       # Custom error handling
│   └── logger.py                 # Logging utilities
│
├── static/
│   ├── style.css                 # Frontend styling
│   └── demo.gif                  # Demo animation (add your GIF here)
│
├── templates/
│   └── index.html                # Main web UI
│
├── grafana/
│   └── grafana-deployment.yaml   # Grafana monitoring deployment
│
├── prometheus/
│   ├── prometheus-configmap.yaml # Prometheus config
│   └── prometheus-deployment.yaml# Prometheus deployment
│
└── FLIPKART_PRODUCT_RECOMMENDER.egg-info/ # Packaging metadata
```

---

## ✨ Features

- **Personalized Recommendations:** Uses real Flipkart product review data to suggest relevant products.
- **Modern LLMOPS Stack:** Dockerized, Kubernetes-ready, and instrumented with Prometheus & Grafana.
- **Robust Data Pipeline:** Modular ingestion, Data versioning, cleaning, and transformation scripts.
- **Production-Ready API:** Flask backend with a clean, responsive frontend.
- **Error Handling & Logging:** Custom exception and logging modules for Debugging & reliability.

---

## 📊 Monitoring & Observability
- **Prometheus**: Collects real-time metrics from the Flask app.
- **Grafana**: Visualizes system health and user activity.

---

## 🖥️ Demo

![Demo GIF](static/demo.gif)

> _Replace `static/demo.gif` with your own screen recording to showcase the app in action!_

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/FLIPKART-PRODUCT-RECOMMENDATION-SYSTEM.git
   cd FLIPKART-PRODUCT-RECOMMENDATION-SYSTEM
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the app:**
   ```bash
   python app.py
   ```
4. **(Optional) Deploy with Docker:**
   ```bash
   docker build -t flipkart-recommender .
   docker run -p 5000:5000 flipkart-recommender
   ```
5. **(Optional) Deploy on Kubernetes:**
   - Use the provided YAML files in `flask-deployment.yaml`, `grafana/`, and `prometheus/`.

---

## 💡 Why Hire Me?
- **Industry-Relevant Skills:** Demonstrates expertise in ML, LLMOPS, cloud-native deployment, and monitoring.
- **End-to-End Ownership:** From data ingestion to production monitoring.
- **Clean Code & Documentation:** Follows best practices for maintainability and scalability.

---

## 📬 Contact

If you like this project or want to discuss opportunities, feel free to connect:
- [LinkedIn](https://www.linkedin.com/in/atharvahatekar)
- [Email](mailto:atharva_hatekar@yahoo.in)

---

> **Star ⭐ this repo if you found it useful!**
