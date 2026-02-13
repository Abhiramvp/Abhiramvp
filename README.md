# 👋 Hi, I’m Abhiram V. P. Premakumar

 **Interests:** Power system optimization • Hardware-in-the-Loop (HIL) testing • Microgrid Controls  
 **Current role:** Postdoctoral Research Associate (Electrical Engineering Dept.), University of Texas at Arlington (UTA)  
 **Open to collaborate on:** Real-time optimization + control, and HIL-validated workflows for (inverter/DC) microgrids and power electronics systems 
 **Reach me:** abhiram2783@gmail.com | +1-682-307-3585

🔗 **Links:**  
- Google Scholar: https://scholar.google.com/citations?user=sKwaUh8AAAAJ&hl=en&oi=ao
- Website: https://github.com/Abhiramvp
- LinkedIn: https://linkedin.com/in/Abhiramvp  
- GitHub/Projects: [https://github.com/Abhiramvp](https://github.com/Abhiramvp?tab=repositories)  

---

## 🔬 What I work on
- Real-time optimization and feedback control design for inverter dominant microgrids, integrating stability-constrained operating points with converter-level control loops  
- Controller-Hardware-in-the-Loop (C-HIL) based validation pipelines for power-electronic control strategies, including repeatable real-time testing and closed-loop performance benchmarking  
- Robust feedback control synthesis for uncertainty-afflicted DC networks with parametric variation, load uncertainty, and dynamic coupling  
- End-to-end convex and semidefinite optimization pipelines for constraint-aware, stability-certified control and operating point computation  
- Optimization modeling and solution pipelines (convex / robust / SDP-style workflows)

---

## 🧰 Skills & Tools
**HIL / Real-time platforms:**  
- Typhoon HIL (HIL 604 RTS, ETH-VE, TestIDE)  
- dSPACE (RTI, ControlDesk, DS1202 HIL), Ethernet communication

**Modeling / Optimization / Simulation:**  
- MATLAB (CVX, YALMIP)  
- Simulink/Simscape, PLECS, PSCAD, PSS/E

**Python:**  
- Power system: pypower, CVXpy, pypower, pandapower, gurobipy
- Data analysis / ML: NumPy, TensorFlow  
- Test automation: pytest

**Embedded & Protocols:**  
- TI C2000 (F28379D) in C (working familiarity with C++)  
- CAPL scripting, Modbus TCP, CAN, Ethernet (HIL/SCADA contexts)

---

## 🧑‍💻 Experience
- **Postdoctoral Research Associate, UTA** (Aug 2025 – Present)  
  - Development of real-time optimization algorithms & control implementation in inverter dominant microgrids

- **Graduate Research Assistant, UTA** (Jan 2021 – Aug 2025)  
  - C-HIL testing for inverter dominant microgrids (MATLAB/dSPACE/Typhoon HIL)  
  - Design and validation of converter control algorithms for uncertainty-afflicted DC microgrids

- **Engineer, Solar Energy Corporation of India (SECI)** (Jul 2019 – Dec 2020)  
  - Feasibility studies of megawatt-scale solar PV projects (PVsyst, MATLAB)

---

## 🎓 Education
- **Ph.D., Electrical Engineering, UTA** (GPA: 4.0/4.0, Jan 2021 – Aug 2025)  
  - Thesis: *Synergistic Control and Optimization in Complex Microgrids*

- **Master’s, Electrical Engineering, IIT Kanpur** (Aug 2017 – Jul 2019)

---

## 📚 Publications

### First-author
- A. V. P. Premakumar, Y. Y. Qian, M. Davoodi, Y. Wan and A. Davoudi, "Robust control of power buffers in DC microgrids," in *IEEE Transactions on Energy Conversion*, vol. 38, no. 1, pp. 89-99, Mar. 2023.  
- A. V. P. Premakumar, Y. Y. Qian, Y. Wan and A. Davoudi, "Optimal control of stochastic power buffers in DC microgrids," in *Proceedings of the 2023 American Control Conference (ACC)*, pp. 3245-3250, 2023.  
- A. V. P. Premakumar, R. Madani and A. Davoudi, "Optimal Power Flow in Uncertain DC Networks," in *IEEE Transactions on Power Systems*, vol. 40, no. 1, pp. 947-956, Jan. 2025.  
- A. V. P. Premakumar, R. Madani and A. Davoudi, "Robust Control of Uncertain DC Microgrids using SOS Programming," in *Proceedings of the 2024 IEEE Energy Conversion Congress and Exposition (ECCE)*, pp. 4335-4340, 2024.  
- V. P. Abhiram, A. B. Shyam, S. R. Sahoo and S. Anand, "Communication topology selection for secondary controllers in DC microgrid," in *Proceedings of the 2019 National Power Electronics Conference (NPEC)*, pp. 1-6, 2019.  
- V. P. Abhiram, A. B. Shyam, S. R. Sahoo and S. Anand, "Stability of DC Microgrid for Different Reduced Communication Topologies," in *Proceedings of the 2019 8th International Conference on Power Systems (ICPS)*, pp. 1-6, 2019.  
- “Accelerated Stable-Optimal Solutions for Inverter dominant Autonomous Microgrids,” (ongoing)

### Co-author / Collaborative works
- Y. Y. Qian, A. V. P. Premakumar, Y. Wan, Z. Lin, Y. A. Shamash and A. Davoudi, "Dynamic event-triggered distributed secondary control of DC microgrids," in *IEEE Transactions on Power Electronics*, vol. 37, no. 9, pp. 10226-10238, 2022.  
- S. Zhou, Y. Qian, Y. Wan, Z. Lin, Y. A. Shamash, A. V. P. Premakumar and A. Davoudi, "On the Resilience Analysis of DC Microgrids With Power Buffer Control," in *IEEE Transactions on Circuits and Systems I: Regular Papers*, vol. 71, no. 9, pp. 4233-4246, 2024.  
- Y. Qian, A. V. P. Premakumar, Y. Wan, Z. Lin, Y. A. Shamash and A. Davoudi, "Event-triggered control of power buffers in DC microgrids over an unreliable network," in *International Journal of Robust and Nonlinear Control*, vol. 35, no. 17, pp. 7142-7158, 2025.  

---

## 🏆 Awards
- Runner-up: 2025 N. M. Stelmakh Outstanding Student Research Award  
- Laxmi and Raj Mrig Endowed Graduate Fellowship (Fall 2024, Spring 2025)  
- ACC 2023 student travel grant; presenter at IEEE ACC 2023 and IEEE ECCE 2024  
- POSOCO Power System Award (PPSA) 2020

---

## 🤝 Let’s connect
If you're building anything around **microgrid optimization/control** or **HIL validation (Typhoon/dSPACE)**, feel free to reach out.
📫 abhiram2783@gmail.com

# 🔬From Model to Deployment

## 1) Robust Control via SOS (ECCE 2024)

### A. Engineering Problem  
DC microgrids with tightly regulated converters behave as constant power loads and can become unstable under uncertainty in loads, line parameters, and source voltages. Stability must be guaranteed across bounded, time-varying uncertainty trajectories.

### B. Algorithm Design  
Developed a robust controller synthesis framework using parameter-dependent Lyapunov functions.  
Converted infinite robust stability conditions into tractable semidefinite programs using sum-of-squares relaxation and lifting techniques.  
Used sequential penalization to recover implementable feedback gains from relaxed solutions.

### C. Real-Time Validation  
Controller gains deployed on dSPACE hardware.  
Network emulated in Typhoon HIL.  
Closed-loop stability verified under structured uncertainty scenarios.

### D. Challenges  


---

## 2) Robust OPF with Affine Policies (IEEE TPS 2025)

### A. Engineering Problem  
DC optimal power flow under uncertain load demand where voltage, generation, and line limits must remain feasible for all admissible uncertainty realizations.

### B. Algorithm Design  
Formulated OPF as a nonconvex QCQP with ellipsoidal uncertainty.  
Designed affine voltage control policies mapping load variations to setpoints.  
Used S-lemma and semidefinite relaxation to eliminate semi-infinite constraints.  
Applied lifting and penalization to ensure physical feasibility.

### C. Real-Time Validation  
Computed affine voltage policies offline.  
Implemented real-time mapping from measured load to voltage commands.  
Validated on IEEE test systems and via controller and hardware in the loop experiments.

### D. Challenges  


---

## 3) Robust Buffer Control (IEEE TEC 2023)

### A. Engineering Problem  
Power buffers interacting with DC microgrids introduce dynamic coupling and parametric uncertainty, requiring guaranteed voltage regulation and stability.

### B. Algorithm Design  
Modeled coupled buffer-network dynamics in state space.  
Derived robust stability conditions using parameter-dependent Lyapunov structures.  
Converted synthesis conditions into convex LMI-based controller design.

### C. Real-Time Validation  
Implemented feedback gains in nonlinear converter simulations.  
Evaluated robustness under parameter variation and load fluctuation.

### D. Challenges  


---

## 4) Stochastic Buffer Control (ACC 2023)

### A. Engineering Problem  
Coordinated control of power buffers under stochastic load variations with performance optimization objectives.

### B. Algorithm Design  
Formulated control as a differential game under probabilistic uncertainty.  
Reduced stochastic dimensionality using probabilistic collocation.  
Applied integral reinforcement learning to approximate optimal policies.

### C. Real-Time Validation  
Evaluated learned policies under stochastic load realizations.  
Benchmarked performance against conventional strategies.

### D. Challenges  


---

## 5) Event-Triggered Secondary Control (IEEE TPEL)

### A. Engineering Problem  
Distributed secondary voltage regulation and current sharing in DC microgrids with limited communication bandwidth.

### B. Algorithm Design  
Developed a dynamic event-triggered control mechanism to reduce communication.  
Proved closed-loop stability and guaranteed positive inter-event times.  
Separated physical and cyber layer models for distributed implementation.

### C. Real-Time Validation  
Implemented distributed controllers with sparse communication updates.  
Validated performance using controller and hardware in the loop experiments.

### D. Challenges  


---

## 6) Stability-Constrained OPF (Ongoing)

### A. Engineering Problem  
Inverter dominant autonomous microgrids require operating points that are both optimal and small-signal stable.

### B. Algorithm Design  
Embedded stability constraints directly into OPF using an augmented Jacobian formulation.  
Convexified the coupled stability and dispatch problem using semidefinite relaxation.  
Accelerated convergence using physics-informed neural network warm starts.

### C. Real-Time Validation  
Evaluated on multi-bus benchmark systems.  
Validated stability-optimal operating points using controller and hardware in the loop experiments.

### D. Challenges  

