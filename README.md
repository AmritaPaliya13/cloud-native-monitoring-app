![Status](https://img.shields.io/badge/status-active-brightgreen)
![Python](https://img.shields.io/badge/python-3.10-blue)
![Docker](https://img.shields.io/badge/built%20with-docker-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

🚀 Cloud Native Monitoring Application

Deploy and monitor a Python micro‑service in a Docker container, with built‑in metrics you can scrape from Prometheus or visualize in Grafana.

📂 Project Structure
.
├── app.py
├── requirements.txt
├── Dockerfile
└── ...
⚡ Quick Start

```bash
Build the image
docker build -t monitoring-app .

Run the container
docker run -p 5000:5000 monitoring-app
🛠 Tech Stack
Python 3.x (Flask/FastAPI core)
Docker
Prometheus + Grafana (optional dashboards)

🤝Contributing
Fork the repo
Create a feature branch
Open a PR 🚀

📸 Screenshot
![Monitoring App](screenshots/monitoring-app.png)


