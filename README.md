# ✋ Hand Grasp Synergy 60-FPS Pure Motion-Graphics Studio
### Kinematic-Muscular Synergy Coupling & Dimensionality Reduction for Underactuated Anthropomorphic Robotic Hands

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Studio-0284c7?style=for-the-badge&logo=github)](https://zedan2552000.github.io/hand-grasp-synergy-motion-studio/)
[![MSc Thesis](https://img.shields.io/badge/MSc%20Thesis-Ain%20Shams%20University-emerald?style=for-the-badge)](https://eng.asu.edu.eg/)
[![FPS](https://img.shields.io/badge/Motion%20Engine-60%20FPS%20Canvas-f59e0b?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Q1 Papers](https://img.shields.io/badge/Literature-10%20Core%20Papers%20(9%20Q1)-purple?style=for-the-badge)](papers/)

---

## 🌟 Overview & Key Features

This interactive, browser-based 60-FPS Motion-Graphics Studio provides real-time biomechanical simulation, signal decomposition, and mechanical transmission analysis for **Eng. Mohamed Zedan's** MSc Thesis at **Ain Shams University** (Faculty of Engineering, Mechatronics Department).

Supervised by:
* **Prof. Dr. Mohamed Hamdy Abdelhafiz** (Professor of Mechatronics & Control)
* **Dr. Mohammed Ibrahim Awad** (Associate Professor of Robotics & Biomechatronics)

### 🚀 Core Modules:
1. **Interactive 60-FPS Biomechanical Twin:** 5-digit articulated robotic hand model with real-time tendon routing, finger joint kinematics, contact pressure detection, and collision feedback across 5 daily objects (Cylinder, Sphere, Key, Precision Disk, Hook Handle).
2. **Biosignal & Synergy Oscilloscope:** Live simulated multi-channel forearm sEMG signals ($M$), NMF muscle synergy activations ($H_k$), and reconstructed joint angles ($\hat{\theta}$).
3. **Mechanical Differential Mechanism:** Real-time simulation of see-saw whiffletree / planetary gear transmissions demonstrating how 1 or 2 motors automatically wrap 5 fingers around irregular objects without sensor feedback.
4. **Ain Shams Data Glove Twin (Dr. Awad's Lab):** 10-flex sensor telemetry and real-time machine learning gesture classification gauge (96.5% accuracy).
5. **Interactive Literature Comparison Matrix:** Sortable, filterable matrix covering all 10 core papers with hardware bills of materials (BOM), inputs, outputs, and supervisor defense talking points.

---

## 📑 Core 10 Research Papers Matrix

| # | Paper Code | Journal & Quartile | System & Sensing | Actuator Count | Synergy Algorithm | VAF / Accuracy | Thesis Role |
|:---:|---|:---:|---|:---:|---|:---:|---|
| **01** | **Scano et al. (2023)** | *IEEE Access* (Q1) | CyberGlove II + 22 sEMG | 4 Synergies | NMF + PCA | **91.27% VAF** | Mathematical proof of shared kinematic-muscular synergies. |
| **02** | **Jarque-Bou et al. (2021)** | *Nature Sci Data* (Q1) | CyberGlove + 31 FSRs + sEMG | Task-Specific | Synchronized Kin-Mus-Force | **Multi-modal ADLs** | Joint angle to contact force mapping in daily tasks. |
| **03** | **Jarque-Bou et al. (2019)** | *Springer JNER* (Q1) | CyberGlove II (77 Subjects) | 3 Primary Synergies | Hierarchical PCA | **51.8% (3) / 82% (12)** | Proves 3 actuators cover 90% of daily grasps. |
| **04** | **Chen et al. (2022)** | *IEEE/ASME T-MECH* (Q1) | 3-Finger Tendon Differential | **3 Motors** | Synergy Mapping Matrix | **15 N Grip Force** | Engineering blueprint for gear-tendon synergy coupling. |
| **05** | **Sun et al. (2022)** | *IEEE T-RO* (Q1) | Dual Differential Transmission | **2 Motors** (20 DOF) | Dual Jacobi Equilibrium | **&gt; 94% Grasp Success** | Mathematical proof that 2 motors cover power & precision. |
| **06** | **Li et al. (2022)** | *IEEE RA-L* (Q1) | 3D-Printed SoftHand | **1 Motor** ($150) | Soft Adaptive Synergy | **24/33 Feix Grasps** | Low-cost 3D-printable rolling-contact joint design. |
| **07** | **Teng et al. (2021)** | *IEEE TNSRE* (Q1) | Delsys Wireless sEMG | Synergy Classifier | NMF-ANLS | **95.2% Accuracy** | Solves muscle force variation (20% to 80% MVC). |
| **08** | **Meattini et al. (2022)** | *IEEE RA-L* (Q1) | Myo Armband + qb SoftHand | Continuous Regression | Self-Supervised DNN + NMF | **14 ms Latency** | Continuous finger control without manual labeling. |
| **09** | **Yeung, Farina (2022)** | *IEEE TBME* (Q1) | HD-sEMG (64 Channels) | Co-Adaptive Limb | Online Unsupervised NMF | **94% Long-term Stability** | Real-time unsupervised adaptation to muscle fatigue. |
| **10** | **Sarwat, Awad (2021)** | *MDPI Sensors* (Q2) | **Ain Shams Data Glove** | 10 Flex + FSR + IMU | Supervised ML (k-NN, SVM) | **96.5% Accuracy** | Foundational supervisor lab baseline to extend into synergies. |

---

## 🛠️ How to Run Locally

Simply open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari):

```bash
# Clone the repository
git clone https://github.com/Zedan2552000/hand-grasp-synergy-motion-studio.git

# Open the studio in your default browser
cd hand-grasp-synergy-motion-studio
start index.html
```

Keyboard Shortcuts:
* `Space`: Play / Pause 60-FPS animation
* `Arrow Right`: Next Paper
* `Arrow Left`: Previous Paper
* `F`: Fullscreen Toggle

---

## 🎓 Academic Defense & Supervisor Integration

Built specifically for meeting preparations with **Prof. Dr. Mohamed Hamdy** and **Dr. Mohammed Awad**:
* **Dr. Hamdy's Question:** *"How do we mathematically reduce 20 joints to 2-4 motors without losing grasp versatility?"*  
  $\rightarrow$ Addressed via Sun et al. (*IEEE T-RO 2022*) and Scano et al. (*IEEE Access 2023*), proving $K=4$ reaches 91.3% VAF and 2 motors cover 94% of grasps via differential transmission.
* **Dr. Awad's Question:** *"What happens when muscle force changes or fatigue sets in, and how do we avoid manual labeling?"*  
  $\rightarrow$ Addressed via Teng et al. (*IEEE TNSRE 2021*) and Yeung, Farina et al. (*IEEE TBME 2022*) using unsupervised adaptive NMF.
