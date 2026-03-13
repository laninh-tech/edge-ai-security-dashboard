# Edge AI Security Dashboard

Real-time smart security monitoring platform powered by YOLOv8, OpenCV, and a modern TypeScript dashboard.

## Overview
This project combines computer vision inference with a responsive web interface to monitor camera streams, detect events, and track system performance in near real time.

## Key features
- Real-time object detection with YOLOv8.
- Live camera/video feed monitoring.
- Event logs and alert-oriented workflows.
- Performance telemetry visualization (FPS and system metrics).
- Frontend dashboard with React + TypeScript.

## Tech stack
- Frontend: React, TypeScript, Vite, Tailwind CSS
- Backend: Python (Flask-based inference service), Node/TypeScript server
- AI/CV: YOLOv8, OpenCV

## Repository highlights
- [QUICKSTART.md](./QUICKSTART.md): fast local setup guide.
- [ARCHITECTURE.md](./ARCHITECTURE.md): high-level architecture and module boundaries.
- [SECURITY.md](./SECURITY.md): security policy and reporting.
- [CONTRIBUTING.md](./CONTRIBUTING.md): contribution workflow.

## Quick start
```bash
git clone https://github.com/laninh-tech/edge-ai-security-dashboard.git
cd edge-ai-security-dashboard
npm install
pip install -r requirements.txt
# Option A: one-command startup (Windows)
run_all.bat
# Option B: run frontend and backend separately
npm run dev
python python_server.py
```

## Suggested production direction
- Add authentication and role-based access.
- Move from local file logs to centralized event storage.
- Containerize inference and UI services for cloud/edge deployment.

## Author
La Quang Ninh  
GitHub: https://github.com/laninh-tech