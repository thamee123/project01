# Hi there, I'm PHONGTHEP! 👋
### 🤖 Control & Automation Engineer | PLC Specialist | Robotic Integrator

I am a dedicated **Control Engineer** with a passion for transforming industrial challenges into automated solutions. My expertise lies in designing robust **PLC logic**, integrating **multi-axis robots**, and developing intuitive **HMI/SCADA** systems to optimize production efficiency.

---

## 🎓 Education

**Kasetsart University, Sriracha Campus**
Bachelor of Engineering in **Electrical and Electronics Engineering**
_Graduated: [may 2026]_ (e.g., May 2026)

* **Key Coursework:** Industrial Control Systems, Robotics and Automation, Microcontroller Programming, Power Electronics.
* **Final Project:** [Briefly mention your final project related to control/automation, e.g., "Design and Implementation of an Automated Sorting System using Vision and PLC."]

---

## 🛠 Technical Skill Set

| Category | Tools & Technologies |
| :--- | :--- |
| **PLC Programming** | Mitsubishi (GX Works 2/3), Siemens (TIA Portal), Omron (Sysmac), Keyence (KV Studio) |
| **Robotics** | Fanuc (KAREL/TP), ABB (RAPID), Yaskawa (Inform), Delta Robot Integration |
| **HMI / SCADA** | Pro-face, GOT2000, WinCC, Ignition, Node-RED |
| **Industrial Network** | Modbus TCP/RTU, EtherCAT, CC-Link, PROFINET, IO-Link |
| **Design & Tools** | AutoCAD Electrical, SolidWorks, Git, Python for Industry 4.0 |

---

## 🏗 System Design & Implementation (Sample Project)

### 🌟 High-Speed Robotic Sorting & Packaging System
This project demonstrates my ability to integrate high-speed vision with precise motion control.

#### **System Architecture**
The system uses a **Centralized Control** architecture where the PLC acts as the master controller, synchronizing a Delta Robot and Vision system over a high-speed EtherCAT network.

http://googleusercontent.com/image_generation_content/0



#### **Key Features:**
* **Real-time Tracking:** Implemented a "Conveyor Tracking" algorithm to sync robot movement with a variable-speed belt.
* **Vision Guidance:** Integrated Keyence CV-X to detect product orientation and send $X, Y, \theta$ coordinates to the robot.
* **Smart Error Handling:** Developed a custom Function Block (FB) for automated recovery sequences to minimize downtime.

#### **Control Logic Example (Structured Text):**
```pascal
// Example: Simple Conveyor Speed Control based on Buffer Level
IF Buffer_Level > 80 THEN
    Conveyor_Speed := Target_Speed * 0.5; // Slow down
ELSIF Buffer_Level < 20 THEN
    Conveyor_Speed := Target_Speed * 1.2; // Catch up
ELSE
    Conveyor_Speed := Target_Speed;
END_IF;
```

---

## 📊 Performance & Experience

* **Cycle Time Reduction:** Optimized robot path planning to reduce cycle time by **15%**.
* **System Reliability:** Designed fail-safe logic that reduced emergency downtime by **25%** across 3 production lines.
* **Standardization:** Created a standardized PLC library (AOI/FB) for common hardware, reducing programming time for new projects by **40%**.

---

## 📫 How to reach me

* **LinkedIn:** [linkedin.com/in/phongthep](https://linkedin.com/in/your-profile)
* **Email:** phongthep.work@email.com
* **Location:** Bangkok, Thailand 🇹🇭

---

### ⚡ GitHub Stats

[![Phongthep's GitHub Stats](https://github-readme-stats.vercel.app/api?username=phongthep&show_icons=true&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)

* **LinkedIn:** [Your Profile Link]
* **Email:** [Your Email Address]
* **Portfolio:** [Link to your website or PDF]

![Phongthep's GitHub Stats](https://github-readme-stats.vercel.app/api?username=phongthep&show_icons=true&theme=tokyonight)
