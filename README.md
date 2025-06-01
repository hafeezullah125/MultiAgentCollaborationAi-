
 Multi-Agent Collaboration System for AI

This project implements a multi-agent reinforcement learning (MARL) system using CityFlow and Python 3.8 for traffic signal optimization.

---

## 🧠 Overview

The system is designed to coordinate multiple intelligent agents using reinforcement learning to optimize traffic flow in a simulated environment using CityFlow.

---

## 📦 Installation

Follow these steps to set up your environment:

```bash
# Step 1: Install Python 3.8 and system packages
sudo apt-get update
sudo apt-get install -y python3.8 python3.8-dev python3.8-distutils curl build-essential cmake

# Step 2: Manually install pip for Python 3.8
curl -O https://bootstrap.pypa.io/pip/3.8/get-pip.py
python3.8 get-pip.py

# Step 3: Test pip installation
python3.8 -m pip --version

# Step 4: Clone CityFlow
git clone https://github.com/cityflow-project/CityFlow.git
cd CityFlow

# Step 5: Install CityFlow using Python 3.8
python3.8 -m pip install .
```

---

## 🚀 How to Run

Once the dependencies are installed, execute the notebook using Jupyter or a Python IDE:

```bash
# If Jupyter is not installed:
python3.8 -m pip install notebook

# Launch Jupyter
jupyter notebook Multi_Agent_Collaboration_System_for_AI.ipynb
```

---

## 📁 Files

- `Multi_Agent_Collaboration_System_for_AI.ipynb`: Main notebook for training and evaluating the multi-agent system.
- `config.json`, `flow.json`, `roadnet.json`: Required CityFlow configuration files (must be placed in the right directory structure).
- `CityFlow/`: CityFlow simulator directory (cloned from GitHub).

---

## 📊 Output

The notebook will generate:
- Graphs of average rewards, speed, and waiting times.
- Evaluation logs.
- Traffic signal phase updates.

---

## 📌 Notes

- Use Python 3.8 strictly due to compatibility with CityFlow.
- Ensure flow and roadnet files are correctly set in `config.json`.
- Simulation parameters like interval and step count can be adjusted for performance tuning.

---

## 📜 License

This project uses open-source components and is intended for academic/research purposes only.
