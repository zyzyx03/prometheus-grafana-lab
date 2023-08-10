# Docker Compose Setup for Monitoring Labs

This repository contains a Docker Compose configuration to set up a monitoring stack using Prometheus, Grafana, cAdvisor, Node Exporter, and MailDev.

## Prerequisites

Make sure you have Docker and Docker Compose installed on your system.

- [Docker Installation Guide](https://docs.docker.com/get-docker/)
- [Docker Compose Installation Guide](https://docs.docker.com/compose/install/)

## Usage

### Clone this repository to your local machine:

``sh
git clone https://github.com/your-username/your-repo-name.git
``

### Start the monitoring stack:
``sh
docker-compose up -d
``

### Access services:

- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000 (Login with admin/admin)
- cAdvisor: http://localhost:8080
- Node Exporter: http://localhost:9100/metrics
- MailDev: http://localhost:1080