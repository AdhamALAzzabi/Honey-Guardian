# Honey-Guardian

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Honey-Guardian is a powerful, multi-honeypot platform built on Docker to emulate diverse network environments for capturing and analyzing cyberattacks. By integrating various honeypots and the ELK stack, it provides a comprehensive solution for proactive threat detection and intelligence gathering.

## Features

* **Diverse Emulation:**  Simulates a wide range of network services (SSH, FTP, HTTP), IoT devices, and even ICS/SCADA systems to attract various threat actors.
* **Dockerized Deployment:** Utilizes Docker containers for isolated, secure, and easily scalable honeypot deployment.
* **ELK Stack Integration:**  Leverages Elasticsearch, Logstash, and Kibana for centralized log management, powerful analysis, and real-time visualization of threat data.
* **User-Friendly GUI:**  Provides an intuitive graphical interface for effortless management and orchestration of honeypots.

## Screenshots
[![Kibana Dashboard](images/Honey-Guardian GUI.png)](#features)


## Installation

### Prerequisites

* Docker
* Docker Compose

### Steps

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/Honey-Guardian.git](https://github.com/your-username/Honey-Guardian.git)
   cd Honey-Guardian
