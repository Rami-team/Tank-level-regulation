# Tank Level Regulation Using PID Control

## Project Overview
This project demonstrates a closed-loop **tank level regulation system** designed and simulated using **Factory I/O** and **Siemens TIA Portal**.

The control strategy ensures accurate and stable level regulation within the defined operating range.

---

## Control Strategy
- Bidirectional control using **charge and discharge valves**
- PID-based regulation for high precision
- Deadband logic to reduce oscillations
- Designed operating range: **0–300 level units**

This approach prioritizes control accuracy and fast settling in the valid range.

---

## Control System
- PLC: **Siemens S7-1200**
- Control method: PID
- HMI monitoring:
  - Setpoint input
  - Actual level display
  - Trends (SP / PV / Output)
  - Alarm indications

---

## Demonstration
Watch the system in operation:

https://youtu.be/9lmV2OHq1no

---

## Screenshots

### Factory IO Tank
![Tank](https://github.com/user-attachments/assets/a3de9b48-014d-4b77-836c-0f97a58787f2)

### HMI Main Screen
![HMI Main](https://github.com/user-attachments/assets/b0e65c9d-824f-4896-93f6-0bfc7f94b15f)

### HMI Alarm & Diagnostics
<img width="930" height="671" alt="HMI Alarm" src="https://github.com/user-attachments/assets/a444aa98-1d57-4979-9113-7eee98a26434" />

### Level Trend
![HMI Trend](https://github.com/user-attachments/assets/9a46f03a-9e90-4baf-b2ff-b6d1f5b74b2f)


---

## Tools & Technologies
- Factory I/O
- Siemens TIA Portal
- PLC Programming (PID Controller)
- HMI Design
- Process Control & Tuning

---

# Performance Notes

- Fast response
- Minimal overshoot
- Stable steady-state behavior
- Designed and tuned for industrially realistic operating conditions

---

## About This Project

This project demonstrates practical PID tuning and tank level control behavior in an industrial automation environment.
