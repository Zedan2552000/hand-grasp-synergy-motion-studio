# ✋ Hand Grasp Synergy 60-FPS Motion-Graphics Studio & MSc Defense Suite
### Kinematic–Muscular Synergy Coupling & Minimal-Actuator Optimization for Anthropomorphic Prosthetic & Exoskeleton Hands

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Studio%20v2.0-0284c7?style=for-the-badge&logo=github)](https://zedan2552000.github.io/hand-grasp-synergy-motion-studio/)
[![Defense Deck](https://img.shields.io/badge/Defense%20Slides-12--Slide%20Animated%20Deck-f59e0b?style=for-the-badge)](https://zedan2552000.github.io/hand-grasp-synergy-motion-studio/Master_Hand_Synergy_Ain_Shams_Defense.html)
[![MSc Thesis](https://img.shields.io/badge/Ain%20Shams%20University-Mechatronics%20MSc-059669?style=for-the-badge)](https://eng.asu.edu.eg/)
[![Literature](https://img.shields.io/badge/Verified%20Literature-18%20Core%20Studies%20(2019--2026)-8b5cf6?style=for-the-badge)](Master_Literature_Review_and_Taxonomy_Matrix.md)

---

## 🌟 Executive Deliverables (Live on GitHub Pages)

Built for **Eng. Mohamed Zedan's** MSc Thesis Defense & Committee Review at **Ain Shams University** (Faculty of Engineering, Mechatronics Department), supervised by:
- **Prof. Dr. Mohamed Hamdy Abdelhafez** (Professor of Mechatronics & Control)
- **Dr. Mohamed Ibrahim Awad** (Associate Professor of Robotics & Biomechatronics)

### 🔗 Direct Interactive Links:
1. 🎬 **[60-FPS Motion-Graphics Studio v2.0 (`index.html`)](https://zedan2552000.github.io/hand-grasp-synergy-motion-studio/)** — Interactive articulated biomechanical hand twin with **animated neural-to-tendon energy particles**, **movable Ring/Little CMC palm arch mode** (Chu 2026 SX-Hand), **visual occlusion tracking test** (Encord EMG-1 / Kavana 2026), live 8-ch sEMG oscilloscope, and 19-paper evidence dossier.
2. 📊 **[12-Slide Animated Defense Deck (`Master_Hand_Synergy_Ain_Shams_Defense.html`)](https://zedan2552000.github.io/hand-grasp-synergy-motion-studio/Master_Hand_Synergy_Ain_Shams_Defense.html)** | **[PDF Deck](Master_Hand_Synergy_Ain_Shams_Defense.pdf)** | **[Editable PowerPoint `.pptx`](Master_Hand_Synergy_Ain_Shams_Defense.pptx)**
3. 📑 **[Master Literature Review & 18-Paper Taxonomy Matrix (`.md`)](Master_Literature_Review_and_Taxonomy_Matrix.md)** | **[Print-Ready PDF (`Master_Literature_Review_and_Taxonomy_Matrix.pdf`)](Master_Literature_Review_and_Taxonomy_Matrix.pdf)**
4. 📚 **[All 18 Papers Zero-Fluff Technical Master Study Guide (PDF)](All_18_Papers_Zero_Fluff_Complete_Master_Guide_Arabic.pdf)** | **[Interactive Web Edition (`.html`)](https://zedan2552000.github.io/hand-grasp-synergy-motion-studio/All_18_Papers_Zero_Fluff_Complete_Master_Guide_Arabic.html)** — 19-page zero-filler cover-to-cover Arabic/English technical dossier for every single paper (exact protocols, hardware BOM, governing equations, symbol glossary, verified metrics & committee Q&A).

---

## 🎯 Core Research Questions (Committee Directives)

- **RQ1 (Cross-Domain Coupling):** What is the biomechanical and mathematical relationship linking joint **Kinematic Synergies** (PCA) and forearm **Muscle Synergies** (NMF) across human grasp taxonomies (**Feix 33 Grasps**), solved via **Mixed Matrix Factorization (MMF)**?
- **RQ2 (Minimal Actuators & Mechanical Stability):** What is the minimum number of actuators (**$K_{min} \le 4$**) sufficient to reproduce daily grasps with **$\text{VAF} \ge 90\%$**, individual joint fidelity (**$\text{ORQ} > 90\%$ & $\text{IRQ}_i > 90\%$** via JGKSE + palm CMC articulation), and verified force-closure stability in **Simulink / Simscape Multibody**?

---

## 📊 Verified 18-Paper Master Literature Matrix (2019–2026)

| # | Citation & Venue | Pillar | Cohort / Dataset / HW | Method | Verified Metrics | Thesis Role |
|---|---|---|---|---|---|---|
| 1 | **Jarque-Bou et al. (2019)** *JNER* | P1: Kinematic | 77 subj, 20 grasps, 17-DoF CyberGlove II | PCA | 3 PCs $>50\%$ VAF; 12 PCs $>80\%$ VAF | Large-cohort kinematic taxonomy baseline |
| 2 | **Teng et al. (2021)** *IEEE TNSRE* | P2: Muscle | 6 grasps × 3 force levels (L/M/H) | NMF + MSC vs LDA | Intra-force 90.2–91.4%; overall 85.8%; cross-force 78.7% | Proves NMF synergy invariance under force shifts |
| 3 | **Sarwat, Maged & Awad (2021)** *Sensors* | P4: ASU Base | Ain Shams Glove (10 flex + 5 FSR + IMU) | Supervised ML | **85% ($\pm 5.1\%$)** stroke rehab accuracy | **Direct Ain Shams institutional HW baseline** |
| 4 | **Li et al. (2022)** *IEEE ICRA* | P3: Hardware | BPI SoftHand (15 joints/19 DoF, $K=1$) | Adaptive + Soft synergies | ~£65 BOM; spring-coupled tendon adaptation | Lower-bound $K=1$ compliant benchmark |
| 5 | **Sun et al. (2022)** *IEEE T-RO* | P3: Hardware | Mini X-Hand (5 fingers + diff palm, $K=2$) | Diff-palm eigengrasps | **29/33 Feix grasps (88%)** | Shows $K=2$ misses 4 precision grasps |
| 6 | **Lapresa et al. (2022)** *Front. Bioeng.* | P1: Modeling | OpenSim `ARMS Hand_Wrist_Model` (26 DoFs) | Scaling + IK | Marker tracking error **$<5\text{ mm}$** | OpenSim anatomical model gold standard |
| 7 | **Yeung & Farina (2022)** *Curr. Opin. BE* | P2: Neural HMI | HD-sEMG, TMR, ONI | BSS & NMF projection | Cross-session synergy invariance | Clinical myoelectric stability rationale |
| 8 | **Olikkal et al. (2022)** *Front. Neurosci.* | P2: Estimation | Continuous sEMG + finger kinematics | SVD/Tensor + Kalman Filter | Smoother continuous pose tracking | Embedded real-time filtering template |
| 9 | **Scano et al. (2023)** *IEEE Access* | P2: Coupling (**RQ1**) | **Ninapro DB2**: 28 subj, 20 grasps | **Mixed Matrix Factorization (MMF)** | **7 joint synergies/subj**, **$R^2 > 0.75$** | **Core RQ1 mathematical engine** |
| 10 | **Meattini et al. (2023)** *IEEE RA-L* | P2: Hybrid AI | 8-ch sEMG → 3 grasp primitives (AR10) | Self-supervised NMF + DNN | **$R^2=0.8423$**, $\text{RMSE}=0.0735$ | Label-free nonlinear sEMG control |
| 11 | **Lapresa et al. (2024)** *BBE* | P1/P3: Force | 8 subj, 21 grasps, Vicon + FSR + **Simscape** | Kin+Force PCA + LDA | **89% LDA accuracy**; higher Simscape stability | **Simscape Multibody dynamic validation** |
| 12 | **Bazina et al. (2024)** *Robotics* | P1: Reduction | **`KIN-MUS UJI`**: 23 ADLs, 16 finger DoFs | Inter-joint linear coupling | 16 DoFs reduced to 5–15 (median 12) | Direct analytical benchmark on local dataset |
| 13 | **West & Hogan (2024)** *IEEE BioRob* | P1: Tasks | 7 subj, 19-DoF CyberGlove | PCA + VAF task compare | 2 PCs $>80\%$ (reach-to-grasp) | Separates static grasp vs active manipulation |
| 14 | **West & Hogan (2025)** *IEEE ICRA* | P1: Subspace (**RQ2**) | 20-DoF Wire-harness ($n=7$) + Piano ($n=5$) | **VAF-CI** + Principal Angles | **3–4 invariant PCs** ($\text{VAF} \ge 90\%$) | **Theoretical proof anchoring $K_{min} \le 4$** |
| 15 | **Pham et al. (2026)** *RAS* | P4: Primitives | 20-DoF exo glove, 13 cleaning tasks, Shadow | **PCA + ProMPs** | 5–7 PCs $\ge 90\%$ VAF, $<10\%$ error | Temporal trajectories in PCA synergy space |
| 16 | **Chu et al. (2026)** *IEEE T-RO* | P3: HW (**RQ2**) | **SX-Hand**: 21 joints (CMC palm), 12 motors | **JGKSE ($\text{ORQ},\text{IRQ} > 90\%$)** | $\text{ORQ}=96.3\%$, $\min(\text{IRQ})=94.6\%$, **33/33 Feix (100%)**, 20 kg | Proves **JGKSE + CMC** hits 100% Feix coverage |
| 17 | **Encord & WD (Oct 2026)** *EMG-1* | P2/P4: Data | **100h** (`8ch-mocap`: 12 subj, 920 takes @ 2kHz) | Continuous 8-ch wrist sEMG | **MAE $4.21^\circ$ vs $9.02^\circ$ CV (-53.3%)**, 0–80 N, occlusion-proof | Next-gen multimodal benchmark (`OP-001/s003/02` verified) |
| 18 | **NVIDIA GEAR (Nov 2026)** *GR00T 2* | P4: VLA AI | Humanoid & 20–22 DoF dexterous hands | **VQ-VAE** + Flow Matching | Stable contact manipulation via latent bottleneck | Confirms synergy bottleneck in 2026 VLAs |

---

## 🚀 4-Phase MSc Execution Roadmap

1. **Phase 1 — Cross-Domain Math:** Run PCA, NMF & MMF jointly across `KIN-MUS UJI` (28 subjects, 26 ADLs) and `Encord EMG-1` (`8ch-mocap`) to quantify Feix coupling (**RQ1**).
2. **Phase 2 — $K_{min} \le 4$ Optimization:** Apply **JGKSE** (ORQ $>90\%$ & IRQ $>90\%$) to isolate minimal flexion eigengrasps + thumb opposition + CMC palm arch (**RQ2**).
3. **Phase 3 — Simscape Dynamics:** Validate force-closure and slip resistance in **Simulink / Simscape Multibody** under external loads.
4. **Phase 4 — Ain Shams Integration:** Upgrade the **Ain Shams Data Glove** pipeline (Sarwat & Awad, 2021) for real-time synergy decoding and MSc defense.
