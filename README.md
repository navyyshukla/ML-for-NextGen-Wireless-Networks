# Machine Learning-Based Resource Allocation in Next-Generation Networks

This repository contains the research paper and associated materials for the project titled: "Machine Learning-Based Resource Allocation and Offloading Strategies for Next-Generation Satellite-Terrestrial and IRS-Assisted Networks".

This research was conducted in collaboration with the EEE Department at BITS Pilani, Goa Campus. The project proposes a Deep Reinforcement Learning (DRL) framework to optimize resource allocation and task offloading in a complex, hybrid wireless network.

---

## 📄 Project Summary

The core of this research is a **Deep Q-Network (DQN) agent** designed to navigate the intricate trade-offs between energy consumption and latency for multiple users. We developed and simulated a novel, unified framework that combines three key technologies:
1.  **Satellite Networks:** To provide broad coverage.
2.  **Terrestrial Networks:** For conventional, high-speed connectivity.
3.  **Intelligent Reflecting Surfaces (IRS):** To intelligently reconfigure the wireless environment and enhance signal strength.

Through extensive simulations, our model demonstrated its ability to adapt to dynamic network conditions and significantly improve overall system performance compared to baseline models.

---

## ✨ Key Features & Contributions

* **Novel Integration Framework:** The research introduces a unified model for a three-component satellite-terrestrial-IRS network, addressing a significant gap in prior studies.
* **Dynamic DRL Solution:** A DQN-based agent dynamically allocates resources and manages task offloading decisions to adapt to changing network conditions like user mobility and channel variations.
* **IRS Optimization:** The system dynamically adjusts the phase shifts of the IRS nodes to maximize the data rate for users offloading tasks to the network edge.
* **Performance Validation:** The framework was rigorously tested over 300 simulation episodes, showing significant improvements in latency, energy efficiency, and total system reward.

---

## 🚀 Tech Stack

* **Simulation Environment:** Python
* **Machine Learning Framework:** TensorFlow
* **Core Algorithm:** Deep Q-Network (DQN) with Experience Replay
* **Network Technologies Modelled:** Satellite-Terrestrial Networks (STNs), Intelligent Reflecting Surfaces (IRS), Mobile Edge Computing (MEC)

---

## 📂 Repository Files

* **[ResearchPaperBITSGOA.pdf](ResearchPaperBITSGOA.pdf):** The full academic paper detailing the system model, methodology, and results.
