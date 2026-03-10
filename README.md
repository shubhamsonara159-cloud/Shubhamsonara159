# Shubham J. Sonara - Mechanical Engineering Portfolio

**MS Mechanical Engineering Candidate** | University of New Haven  
📧 Shubhamsonara159@gmail.com | 📍 New Haven, CT  
🔗 [LinkedIn](https://www.linkedin.com/in/shubhamsonara/) | 🐙 [GitHub](https://github.com/shubhamsonara159-cloud)

---

## 👨‍🎓 ABOUT ME

I am a **Mechanical Engineering graduate student** at the University of New Haven with a passion for **design, analysis, and optimization** of mechanical systems. My academic journey has equipped me with strong foundations in **Computer Aided Engineering (CAE)** , **Finite Element Analysis (FEA)** , **Computational Fluid Dynamics (CFD)** , and **Composite Materials**.

I thrive at the intersection of **theoretical mechanics** and **practical engineering solutions**. Every project I undertake is driven by curiosity to understand "why" things work and "how" they can be improved.

---

## 🎯 PROFESSIONAL INTERESTS

| Domain | My Focus |
|--------|----------|
| **⚙️ Design & Manufacturing** | Creating efficient, manufacturable designs with optimized performance-to-weight ratios |
| **🔬 R&D & Product Development** | Translating concepts into validated designs through simulation and testing |
| **🤖 Robotics & Automation** | Structural analysis of robotic components, lightweight design for dynamic systems |
| **📦 Supply Chain & Logistics** | Understanding how design decisions impact manufacturing, assembly, and distribution |
| **🛰️ Aerospace & Defense** | High-performance composite structures for extreme environments |

---

## 💡 MY ENGINEERING PHILOSOPHY

> *"Good design is invisible. Great design is felt through performance, reliability, and efficiency."*

I believe that successful mechanical engineers don't just analyze components—they understand the **entire ecosystem**: how parts are made, how they fail, how they interact, and how they impact the bigger system. Whether it's a CubeSat bracket surviving launch vibrations, a CFRP pump shaft resisting corrosion, or a microchannel cooling a high-heat-flux chip, every detail matters.

---

## 🛠️ TECHNICAL SKILLS

| Category | Skills & Tools |
|----------|----------------|
| **FEA** | Ansys Workbench (Static Structural, Modal, Nonlinear Contact), Mesh Convergence, Stress Analysis |
| **Composites** | Ansys ACP (Composite Prep/Post), Tsai-Wu Failure Criterion, Ply Trimming, Stackup Optimization |
| **CFD** | COMSOL Multiphysics (Conjugate Heat Transfer, Laminar Flow) |
| **CAD** | Ansys SpaceClaim, Parametric Modeling |
| **Materials** | Ti-6Al-4V, AISI 303 Stainless Steel, Al 6061, Steel A36, AISI 1045, IM9 Carbon Fiber/Epoxy |
| **Analysis** | Stress Concentration Factors (Peterson), Thermal Management, Safety Factors, Modal Analysis, Failure Analysis |
| **Validation** | Theory-Experiment Correlation, Error Analysis, Mesh Independence Studies, Force Reaction Validation |
| **Soft Skills** | Technical Writing, Data Visualization, Project Documentation, Presentation |

---

# 🤖 Research Work: Dual Robotic Arm Teleoperation via Learn-from-Demonstration

> **Research Assistant** | Mechatronics Lab, University of New Haven  
---

## 📋 PROJECT OVERVIEW

### 🎯 What I Did

As a **research assistant in the Mechatronics Lab**, I contributed to developing a **gesture-based teleoperation system** that enables intuitive control of **dual UR3e robotic arms** using a **Leap Motion sensor**. 

**The concept is simple but powerful:**  
👉 *Your hands become the robot's hands – in real time.*

When I move my hand forward, the robot moves forward. When I open my hand, the gripper opens. When I close my fist, the gripper closes. Both arms work together, mirroring my bimanual coordination naturally.

---

## 🎥 THE VIDEO: ROBOT MIMICKING HAND MOTION

### Watch: Dual UR3e Robots Controlled by Hand Gestures

[[Dual Robot Teleoperation Demo](https://drive.google.com/file/d/1CPsMGz-BkGvJhTftR8GT6BbFpRhv_09h/view?usp=drive_link)]

> *Click the image above to watch the full demonstration – my hand movements control both UR3e arms simultaneously in real-time*

### What You'll See in the Video:

| Timestamp | Demonstration |
|-----------|---------------|
| **0:00** | System setup – Leap Motion sensor facing upward, two UR3e robots on table |
| **0:15** | Calibration – Mapping my hand position to robot home position |
| **0:30** | Single-arm control – Left hand moves left robot forward/backward, left/right, up/down |
| **1:00** | Dual-arm coordination – Both hands control both robots independently |
| **1:30** | Gripper control – Open hand → gripper opens, Closed fist → gripper closes |
| **2:00** | Complex task – Picking up objects with both arms simultaneously |
| **2:30** | Response time test – Quick hand motions with instant robot reaction (visible in real-time) |
| **3:00** | Precision task – Positioning objects with millimeter accuracy |

---

## 📝 THE RESEARCH BEHIND THE VIDEO

### 🧠 How It Works

| Component | Function |
|-----------|----------|
| **Leap Motion Sensor** | Tracks hand position (x, y, z) and orientation at 60 frames/second |
| **Python Script** | Processes hand data, applies filtering, calculates target positions |
| **RTDE Protocol** | Sends commands to UR3e robots at 10Hz over Ethernet |
| **UR3e Robots** | Two 6-DOF collaborative robots that mirror hand movements |

### The Math (Simple Version)

When I move my hand, the robot calculates its new position using:

# 🌡️ Publication : Enhanced Thermal-Hydraulic Performance of a Converging-Diverging Microchannel Heat Sink with Transverse Slots

> **Published Researcher | Advanced Fluid Mechanics**  
> **DOI: [[10.20944/preprints202512.2550.v1](https://doi.org/10.20944/preprints202512.2550.v1)]**

### 🎯 Objective

Design and analyze a novel **Slotted Converging-Diverging (S-CD) microchannel heat sink** to address the fundamental limitation of conventional microchannels: **thermal boundary layer thickening** that restricts heat transfer in high-heat-flux electronics (>100 W/cm²).

### 💡 My Innovation

I proposed and validated a **Slotted Converging-Diverging (S-CD) geometry** where:
- ✅ **Transverse slots** are placed in diverging sections
- ✅ Slots create **micro-jets** that disrupt boundary layers
- ✅ **Vortical mixing** enhances heat transfer without extra pumping power
- ✅ **Synergistic effect** combines CD vortices + slot-induced mixing

### 🛠️ Methodology

| Aspect | Details |
|--------|---------|
| **Software** | COMSOL Multiphysics - Conjugate Heat Transfer Module |
| **Physics** | 3D laminar flow, conjugate heat transfer, temperature-dependent fluid properties |
| **Geometry** | Straight (S-MC), Converging-Diverging (CD-MC), Slotted CD (S-CD-MC) |
| **Mesh** | 2,036,856 domain elements with inflation layers at fluid-solid interfaces |
| **Validation** | Compared with Shah-London correlation (±4% for Nusselt number) |

### 📊 KEY RESULTS

| Metric | Straight MC | CD-MC | S-CD-MC (My Design) | Improvement |
|--------|-------------|-------|---------------------|-------------|
| **Peak Temperature** | 358.4 K | 340.1 K | **332.9 K** | **21.4% ↓ vs CD** |
| **Thermal Resistance** | Highest | 7.3×10⁻³ K/W | **6.0×10⁻³ K/W** | **28% ↓ vs CD** |
| **Pressure Drop** | Highest | 6.93 kPa | **6.91 kPa** | **No penalty!** |
| **Nusselt Number** | Baseline | Moderate | **+31% enhancement** | **31% ↑** |
| **Friction Factor** | Baseline | Moderate | **+8% increase** | **Minimal** |
| **PEC (Performance)** | — | 1.00 | **1.27** | **27% overall ↑** |

### Key Finding

> *"The S-CD design achieves 31% better heat transfer with only 8% increase in friction factor – resulting in a 27% overall performance improvement with zero additional pumping power requirement."*

### Publication Details

**Authors:** Shubham J. Sonara  
**Subject:** Advanced Fluid Mechanics 6630-01  
**Professor:** Dr. Sumith Yesudasan, Ph.D.  
**Institution:** University of New Haven

## 📂 FEATURED PROJECTS

| # | Project | Description | Tools | Status |
|---|---------|-------------|-------|--------|
| **1** | **Stress Concentration Analysis** | FEA validation of Peterson's Kt factors for plate with hole, cantilever beam, and shoulder fillet | Ansys Static Structural | ✅ Complete |
| **2** | **CubeSat Electronics Bracket** | Aerospace bracket design for CubeSat launch survival - 10g acceleration, modal analysis, 2 iterations | Ansys Workbench | ✅ Complete |
| **3** | **CFRP Vertical Pump Shaft** | Composite shaft design for vertical pump using IM9 carbon fiber/epoxy with ply optimization | Ansys ACP, Ansys Mechanical | ✅ Complete |

---

# 🔬 PROJECT 1: Stress Concentration Analysis – FEA Validation vs Peterson's Theory

**Ansys Workbench Simulation & Analytical Correlation Study**

## 📖 Overview
This project validates Finite Element Analysis (FEA) accuracy by comparing simulated stress concentrations against **Peterson's Theoretical Factors ($K_t$)**. It serves as a technical benchmark for mesh sensitivity and structural reliability.

## 🚀 Key Achievements
* **High Accuracy:** Achieved a **2.2% correlation** between FEA and Theory for complex geometries.
* **Mesh Optimization:** Proved that a **0.025" refinement** is the "sweet spot" for capturing peak stress gradients at holes and fillets.
* **Geometric Insight:** Demonstrated that changing geometry (Moment of Inertia) is **5x more effective** at reducing stress than changing materials.

## 📊 Results 
* **Plate with Hole (d=1.0"):** Theory $K_t$ = 3.24 | FEA $K_t$ = 3.31 | **Error: 2.2%**
* **Shoulder Fillet (r/d=0.3"):** Theory $K_t$ = 1.52 | FEA $K_t$ = 1.55 | **Error: 2.2%**
* **Beam Bending (2"x3"):** Theoretical stress = 7,333 psi | FEA stress = 8,653 psi | **Result: Validated**
* **Key Insight:** 0.025" mesh refinement is mandatory for capturing peak stress; coarse meshes underestimate loads by >10%.


## 🛠️ Tools Used
* **Simulation:** Ansys Workbench (Static Structural)
* **Verification:** Peterson’s Stress Concentration Formulas
* **Documentation:** 57-Page Detailed Technical Report

---
### 📂 Documentation
[[Click here to view Stress Concentration Analysis Technical Report](https://drive.google.com/file/d/1_JJMr1fJPw6OwN85NkwjqSGbb5CWG9P4/view?usp=drive_link)] 

---
# 🛰️ PROJECT 2: CubeSat Electronics Mounting Bracket Analysis
**Aerospace Structural Design, Nonlinear FEA & Modal Validation**

## 📖 Overview
This project focuses on the design and structural validation of a mounting bracket for a CubeSat satellite enclosure. The goal was to engineer a solution that survives extreme **10g launch acceleration** while maintaining high natural frequencies to avoid resonance.

## 🚀 Key Achievements
* **72% Stress Reduction:** Optimized bracket geometry in Iteration 2 to significantly lower peak stresses under X, Y, and Z loading.
* **Resonance Mitigation:** Increased the 1st natural frequency from 123 Hz to **281 Hz** (exceeding the 65 Hz aerospace requirement by 4.3x).
* **Enhanced Safety:** Improved the minimum Factor of Safety (FoS) from **1.43 to 2.14** through strategic material selection (AISI 303) and profile refinement.

## 📊 Technical Comparison
| Metric | Requirement | Iteration 1 (Ti-6Al-4V) | Iteration 2 (AISI 303) | Status |
|:---|:---|:---|:---|:---|
| **Max Stress (X-Axis)** | - | 293.9 MPa | **81.3 MPa** | 72% ↓ |
| **Min Safety Factor** | > 1.5 | 1.43 | **2.14** | ✅ PASSED |
| **1st Nat. Frequency** | > 65 Hz | 123 Hz | **281 Hz** | ✅ EXCEEDED |
---

## 🛠️ Engineering Competencies
* **Nonlinear FEA:** Simulated frictional contacts (µ=0.2) and large deflections for realistic load path analysis.
* **Dynamic Analysis:** Performed modal analysis to determine mode shapes and ensure vibration isolation.
* **Aerospace Standards:** Validated designs against high-G quasi-static launch loads.

---
### 📂 Documentation
[[Click here to view Simulation of CubeSat Electronics Assembly Report](https://drive.google.com/file/d/1kzxxJiW3C-UOEjoettPY4SImIeP1KPZJ/view?usp=drive_link)]

---


# 🔧 PROJECT 3: CFRP Vertical Pump Shaft Analysis
**Composite Material Design, Ply Optimization & Tsai-Wu Failure Validation**

## 📖 Overview
This project involves the structural design and optimization of a **Carbon Fiber Reinforced Polymer (CFRP)** shaft for industrial vertical pumps. The study focuses on replacing traditional steel with IM9 Carbon Fiber/Epoxy to provide superior corrosion resistance and a high strength-to-weight ratio under multi-axial loading.

## 🚀 Key Achievements
* **1265% Safety Margin Boost:** Engineered an iterative layup strategy that increased the Margin of Safety (SM) from **0.9 to 12.287**.
* **Strategic Weight Reduction:** Successfully implemented **ply trimming** (dropping 90° layers 4 and 12) to minimize mass while maintaining a robust SM of 10.59.
* **Failure Mode Validation:** Utilized the **Tsai-Wu Failure Criterion** to ensure the Inverse Reserve Factor (IRF) remained at an elite level of **0.05**.

## 📊 Quick Results Table
| Configuration | Layup Strategy | Total Plies | Margin of Safety (SM) | IRF | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Initial** | [0/45/-45/90]s × 1 | 8 (7 trimmed) | 0.9 | 0.06 | Baseline |
| **Improved** | [0/45/-45/90]s × 2 | 16 | 12.287 | 0.04 | High Strength |
| **Optimized** | **[0/45/-45/90]s × 2*** | **14** | **10.591** | **0.05** | ✅ **FINAL** |
*\*Optimized design utilizes targeted ply-dropping for weight efficiency.*

---

## 🛠️ Tools Used
* **Simulation:** Ansys Workbench (Static Structural & ACP/Composite PrepPost)
* **Analysis:** Tsai-Wu Failure Theory, Hygrothermal Expansion Modeling
* **Documentation:** 27-Page Comprehensive Technical Report

---
### 📂 Documentation

[[Click here to view CFRP Vertical Pump Shaft Analysis Report](https://drive.google.com/file/d/1nvamfVeiSXRf3xH7h8CjGFaJaigAe4AB/view?usp=drive_link)]

---





## 🎨 DESIGN SHOWCASE - CAD MODELS & ASSEMBLIES

> *Exploring form, function, and manufacturability through parametric design*

## 🏭 Featured Design: Centrifugal Pump Assembly

**Software:** SolidWorks  
**Type:** Full Assembly | Industrial Pump Design

| Preview | Details |
|---------|---------|
| <img width="665" height="393" alt="image" src="https://github.com/user-attachments/assets/fbb30899-eb04-49b8-9218-e39647cca476" />
 | **Centrifugal Pump**<br>• Complete pump assembly with stand<br>• CFRP shaft integration (see Project 3)<br>• Industrial application-ready design |

### 📐 Design Features
| Feature | Description |
|---------|-------------|
| ✅ **Extrude- feature** | Thin-wall stand for lightweight support |
| ✅ **Curved impeller vanes** | Optimized for fluid flow efficiency |
| ✅ **Volute casing** | Spiral design for pressure conversion |
| ✅ **Modular assembly** | Easy maintenance and part replacement |

### 📁 CAD Files
| File | Description | Format | Link |
|------|-------------|--------|------|
| **Full Pump Assembly** | Complete centrifugal pump | .SLDASM |CAD File
[[STL File](https://drive.google.com/file/d/1Ow6IMRqj_t4rm53GcW-qntSOM763Eczx/view?usp=drive_link)]


### 🎥 Animation
[[Watch Animation](https://drive.google.com/file/d/1yl3Kv6atwfIJSos7mL0MnHumhGoIOO4X/view?usp=drive_link)]
*Click to view the full pump assembly rotation*


### 🔧 Featured Design: Mechanical Jaw Assembly

**Software:** [SolidWorks]  
**Type:** Parametric Solid Model | Manufacturing-Ready Design

| Preview | Details |
|---------|---------|
| *<img width="848" height="560" alt="image" src="https://github.com/user-attachments/assets/0b040862-ccd9-4aa7-97ed-f41bef10ac1d" />
 | **Base Jaw Component**<br>• Precision machined interface<br>• Optimized for grip strength<br>• Manufacturable design with draft analysis |


### 📐 Design Features
- ✅ Parametric dimensions for easy modification
- ✅ Manufacturing considerations (draft angles, fillets)
- ✅ Assembly-ready with proper tolerances
- ✅ Stress-optimized geometry

---

## 🎥 DESIGN VISUALIZATION

### Animation / Motion Study
[[Watch Animation](https://drive.google.com/file/d/1xuxxkCB-Fr_ETgu9kvBzxQl9QUUzzdvy/view?usp=drive_link)]
> *📌 **Note:** Click the link above to view the jaw mechanism in motion*
### CAD File
[[STL File](https://drive.google.com/file/d/1DHjSgzLE-1GvEyVzbTtuvgDfAPWRScHn/view?usp=drive_link)]

---

### 🔧 Featured Design: Porsche GT3 RS Side View Design
**Software:** [SolidWorks]  
**Type:** Automotive surface modeling

## 🎥 DESIGN VISUALIZATION

### Animation / Motion Study
[[Watch Animation](https://drive.google.com/file/d/133JVbjB6clYyYMkEWL70kwWiYvH3xSBV/view?usp=drive_link)]
### CAD File
[[STL File](https://drive.google.com/file/d/13apAdldV3YJVNDy6NKGdVGBNvTroLUgo/view?usp=drive_link)]

## 💡 DESIGN PHILOSOPHY

> *"A well-designed part isn't just strong—it's manufacturable, serviceable, and elegant."*

Each design in this showcase represents:
- ✅ **Manufacturing-first approach** - Draft angles, tool access, assembly sequence considered
- ✅ **Parametric flexibility** - Easy modifications for design iterations
- ✅ **Clear communication** - Detailed drawings with GD&T
- ✅ **Real-world application** - Designed for actual production

---

## 📬 LET'S CONNECT

I'm actively seeking opportunities in:
- 🔧 **Design Engineering**
- 🔬 **R&D / Product Development**
- 🤖 **Robotics & Automation**
- 📦 **Supply Chain Engineering**

**Shubham J. Sonara**  
📍 University of New Haven, MS Mechanical Engineering  
📧 shubham.sonara@example.com  
🔗 [LinkedIn](https://linkedin.com/in/shubham-sonara)  
🐙 [GitHub](https://github.com/shubhamsonara159-cloud)

---

⭐ *If you find my work interesting, please star this repository or connect with me on LinkedIn!*
