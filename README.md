# ⚙️ Advanced Nonlinear Control — Inverted Pendulum, ROV & J-Q Stabilization

> A technical project applying **nonlinear control theory**, **Lyapunov stability**, and **feedback linearization**  
> completed as part of the *Advanced Nonlinear Control* course in the **Erasmus Mundus MIR Programme** at Université de Toulon (2025).

---

## 🎯 Objective

The aim of this project was to implement and compare advanced nonlinear control techniques  
for different dynamic systems — from classic mechanical models to underwater robots —  
and to analyze their stability using **Lyapunov functions** and **feedback linearization**.

Key control topics explored:
- LQR and RK4 simulation for **Inverted Pendulum Stabilization**  
- **Vector field visualization** and **Lotka–Volterra dynamics**  
- **Lyapunov level set analysis** for local/global stability  
- **Jurdjevic–Quinn control design**  
- **Feedback Linearization + PID** for an underwater ROV (depth & pitch control)

---

## 📂 Repository Structure

| Path | Description |
|------|--------------|
| **advance_control_report.pdf** | Full report including simulations, equations, and system analysis |
| **MATLAB/Simulink files** | Implementation of LQR, RK4 solvers, Lyapunov-based controllers |
| **README.md** | Overview and project documentation (this file) |

---

## 🧩 Implemented Systems

| System | Technique | Result |
|--------|------------|--------|
| **Inverted Pendulum** | LQR + RK4 Solver | Stable upright equilibrium with minimal oscillation |
| **Lotka–Volterra System** | J-Q Stabilization | Controlled convergence to closed orbits |
| **Mass–Spring System** | Lyapunov Energy Method | Demonstrated asymptotic energy decay |
| **Turtlebot Differential Drive** | Feedback Linearization | Tracked sinusoidal path with PD control |
| **ROV Depth & Pitch Control** | PID + Linearization Compensation | Improved response and reduced overshoot |

---

## 📊 Key Insights

- The **Jurdjevic–Quinn method** effectively stabilizes nonlinear systems using Lyapunov feedback.  
- **Feedback linearization** simplifies complex robot dynamics, improving tracking accuracy.  
- For underwater vehicles, **PID alone is insufficient** — linearization feedback dramatically reduces overshoot and settling time.  
- Lyapunov analysis confirmed **local stability** in all implemented systems.  

---

## 🧠 Tools & Methods

- **MATLAB / Simulink** – modeling, solver implementation, and simulation  
- **Lyapunov Stability Theory** – stability verification and energy decay analysis  
- **Feedback Linearization** – applied to robotic and underwater control systems  
- **J-Q Stabilization** – nonlinear control law design and verification  

---

## 👩‍🔬 Authors

**Hyejoo Kwon · Akira Techapattaraporn · Mukesh Reddy**  
📍 Erasmus Mundus Master’s in *Marine & Maritime Intelligent Robotics (MIR)*  
📅 Submitted: October 2025  

🔗 [GitHub Repository](https://github.com/S1194789/Advanced_Nonlinear_Control)
