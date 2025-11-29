# DevOps
# Self-Healing Uptime Monitor

## Overview
A DevOps automation tool that monitors website uptime and automatically attempts to restart the service if it fails.

## Tech Stack
* **Language:** Bash & Python
* **Containerization:** Docker
* **Cloud:** AWS EC2
* **Logic:** Loop-based HTTP status checking

## How to Run
```bash
docker build -t uptime-monitor .
docker run -p 8000:8000 uptime-monitor
