# 🧮 Flask Calculator App (Dockerized)

This is a simple web-based calculator built with Python using the Flask framework. The app performs basic arithmetic operations: addition, subtraction, multiplication, and division. It's fully Dockerized for easy deployment.

---

## 🔧 Features

- Add, subtract, multiply, divide two numbers.
- Lightweight Flask-based web app.
- Dockerized for container-based execution.
- Accessible via web browser (default port: `5000`).

---

## 🚀 Live Docker Image

You can pull and run the app directly using the Docker Hub image:

👉 **Docker Hub:** [ejangirr/calculator-app](https://hub.docker.com/r/ejangirr/calculator-app)

```bash
docker pull ejangirr/calculator-app
docker run -p 5000:5000 ejangirr/calculator-app
