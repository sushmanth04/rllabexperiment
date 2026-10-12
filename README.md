# Rl-lab-experiments
# Reinforcement Learning Laboratory Experiments

Welcome to the **Reinforcement Learning Lab Experiments** repository. This repository contains a structured collection of Jupyter Notebooks mapping out core Reinforcement Learning (RL) concepts, ranging from foundational agent-environment interactions to advanced Dynamic Programming and Temporal Difference learning methods.

---

## 📋 Table of Contents
* [Overview](#overview)
* [Laboratory Syllabus Structure](#laboratory-syllabus-structure)
* [File Mapping](#file-mapping)
* [Prerequisites & Installation](#prerequisites--installation)
* [Usage](#usage)

---

## 🔍 Overview
This repository serves as a comprehensive practical guide to Reinforcement Learning. It implements fundamental algorithms using standard tools like **Gymnasium (OpenAI Gym)** to simulate environments and train intelligent agents. 

---

## 🎯 Laboratory Syllabus Structure

The experiments in this repository are organized according to the following syllabus framework:

1. **Foundations**: Implementation of a basic Reinforcement Learning System detailing the Agent, Environment, State, Actions, and Reward.
2. **Multi-Armed Bandits**: Implementation of Multi-Armed Bandits using the OpenAI Gym API.
3. **Greedy Strategies**: Implementation of a Pure Greedy Agent.
4. **Exploration vs. Exploitation**: Implementation of the Epsilon-Greedy (\(\epsilon\)-greedy) policy.
5. **Action-Selection Policies**: Implementation of the Softmax exploration policy.
6. **Optimism in the Face of Uncertainty**: Implementation of the Upper Confidence Bound (UCB) policy.
7. **Bayesian Bandit Strategies**: Implementation of the Thompson Sampling policy.
8. **Environment Anatomy**: A comprehensive study on Environment Types using OpenAI Gym tools.
9. **Real-World Application**: A case study on Ad Optimization using Multi-Armed Bandits.
10. **Markov Decision Processes (MDPs)**: Formulations and solutions using **Value Iteration** and **Policy Iteration**.
11. **Dynamic Programming**: Optimizing agent policies using Model-Based Reinforcement Learning.
12. **Temporal Difference (TD) Learning**: Model-Free prediction/control implemented inside the **Taxi-v3** environment.

---

## 📂 File Mapping

The notebook files inside this repository align directly with the syllabus experiments:

| Experiment / Topic | Associated Notebook File(s) |
| :--- | :--- |
| **1. RL Foundations (Agent/Env)** | `labexp-1.ipynb`, `labexp1.1.ipynb` |
| **2. Multi-Armed Bandits Intro** | `labexp2.ipynb` |
| **3. Greedy Agent** | `labexp3.ipynb` |
| **4. Epsilon Greedy Policy** | `labexp4.ipynb` |
| **5. Softmax Policy** | `labexp5.ipynb` |
| **6. Upper Confidence Bound (UCB)** | `labexp6.ipynb`, `labexp6.1.ipynb` |
| **7. Thompson Sampling** | `labexp6.2.ipynb` |
| **8. Environment Types Study** | `labexp7.ipynb` |
| **9. Ad Optimization Case Study** | `labexp8.ipynb` |
| **10. MDP: Value & Policy Iteration** | `labexp9.ipynb`, `labexp10.ipynb` |
| **11. Dynamic Programming & Model-Based RL**| `labexp11.ipynb` |
| **12. TD Learning (Taxi-v3)** | `TDPrediction.ipynb`, `Taxi_Problem.ipynb` |

---

## ⚙️ Prerequisites & Installation

To run these experiments locally, ensure you have Python 3.8+ installed along with the required dependencies.

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Rl-lab-experiments
   ```

2. **Install dependencies:**
   ```bash
   pip install numpy pandas matplotlib jupyter gymnasium
   ```
   *(Note: Older notebooks might reference `gym`. For modern compatibility, `gymnasium` is recommended).*

---

## 🚀 Usage

1. Launch the Jupyter Notebook environment:
   ```bash
   jupyter notebook
   ```
2. Navigate to the desired experiment (e.g., `Taxi_Problem.ipynb` for the TD Learning experiment).
3. Run the code cells sequentially to visualize agent training curves, state tables, and total cumulative rewards.
