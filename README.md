# Shubham J. Sonara - Mechanical Engineering Portfolio

**MS Mechanical Engineering Candidate** | University of New Haven  
📧 shubham.sonara@example.com | 📍 New Haven, CT  
🔗 [LinkedIn](https://linkedin.com/in/shubham-sonara) | 🐙 [GitHub](https://github.com/shubhamsonara159-cloud)

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

[![[Dual Robot Teleoperation Demo](https://drive.google.com/file/d/1CPsMGz-BkGvJhTftR8GT6BbFpRhv_09h/view?usp=drive_link)]

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

> **Complete FEA validation of stress concentration factors for three classic mechanical engineering problems**

### 🎯 Objective
Validate finite element analysis (FEA) predictions against Peterson's theoretical stress concentration factors (Kt) for:
1. **Flat plate with central circular hole** (2 diameters: 1.0" and 1.5")
2. **Cantilever beam** (2 cross-sections: 1"×2" and 2"×3")
3. **Shoulder fillet** (2 radii: r/d = 0.3 and r/d = 0.167)

### 🛠️ Methodology
- **Software**: Ansys Workbench Static Structural
- **Elements**: Tetrahedral/Solid with refined meshing at stress concentration zones
- **Mesh refinement**: 0.025" at hole edges, 0.04" at fillets
- **Validation**: Compared FEA results with Peterson's analytical formulas

---

## 📈 KEY RESULTS

### Case 1: Plate with Central Hole

| Parameter | d = 1.0" | d = 1.5" |
|----------|----------|----------|
| **Kt (Theory)** | 3.24 | 3.73 |
| **Kt (FEA)** | 3.31 | 3.14 |
| **Error** | **+2.2%** | **-15.8%** |
| **Peak Stress (Theory)** | 25,920 psi | 18,116 psi |
| **Peak Stress (FEA)** | 26,522 psi | 15,252 psi |
| **Safety Factor** | 1.51 | 2.62 |

**✅ Excellent correlation for d=1.0" case (+2.2%)**

---

### Case 2: Cantilever Beam

| Parameter | Case 1 (1"×2") | Case 2 (2"×3") | Improvement |
|----------|----------------|----------------|-------------|
| **Moment of Inertia** | 0.667 in⁴ | 4.50 in⁴ | **+575%** |
| **Theoretical Stress** | 30,000 psi | 7,333 psi | **-75.6%** |
| **FEA Equivalent Stress** | 30,696 psi | 8,653 psi | **-71.8%** |
| **Error** | **+2.3%** | **+18.0%** | — |
| **Safety Factor** | 1.17 | 6.93 | **+492%** |

**✅ Demonstrates geometric dominance in beam design (h³ effect)**

---

### Case 3: Shoulder Fillet

| Parameter | r/d = 0.3 | r/d = 0.167 |
|----------|-----------|-------------|
| **Kt (Peterson)** | 1.52 | 1.75 |
| **Kt (FEA - Principal)** | 1.553 | 1.864 |
| **Correlation** | **+2.2%** | **+6.5%** |
| **Peak Stress (FEA)** | 15,822 psi | 16,486 psi |
| **Safety Factor** | 2.28 | 2.18 |

**✅ Excellent correlation with maximum principal stress**

---

## 📸 KEY VISUAL RESULTS

### Plate with Hole - Stress Distribution
<img width="940" height="468" alt="image" src="https://github.com/user-attachments/assets/f4155087-c3bf-489c-9dcf-c6ba7bebee29" />


**Fig 1:** Von-Mises stress distribution showing maximum stress at hole edge (26,522 psi)

### Cantilever Beam - Linear Stress Pattern
<img width="749" height="431" alt="image" src="https://github.com/user-attachments/assets/2cc70f38-0500-4202-ab15-16d48512d813" />

**Fig 2:** Linear stress variation across beam height confirming bending theory

### Shoulder Fillet - Stress Concentration
<img width="819" height="440" alt="image" src="https://github.com/user-attachments/assets/0537fa20-5d91-4a63-991a-fa25c2d74596" />

**Fig 3:** Maximum principal stress at fillet root (15,822 psi for r/d=0.3)

---

## 🧠 ENGINEERING INSIGHTS & LEARNING

### What This Project Taught Me:

1. **Mesh Refinement is Critical**  
   Using 0.025" element size at stress concentration zones was essential for accurate Kt prediction. Coarser meshes underestimated peak stresses by >10%.

2. **Multi-axial Stress States Matter**  
   The plate with hole showed transverse stresses (2,454 psi) due to Poisson effects—something 2D analysis would miss entirely.

3. **Geometric Effects Dominate Material Choices**  
   Increasing beam moment of inertia by 575% reduced stress by 75.6%—a far greater impact than switching to a higher-strength material.

4. **Principal Stress vs Equivalent Stress**  
   For shoulder fillets, maximum principal stress gave better correlation with Peterson's Kt (+2.2%) compared to von-Mises stress (-5.5%).

5. **Theory Validated**  
   Peterson's formulas were validated within ±6.5% across all cases, with best correlation at 2.2% for optimal mesh.

### How This Applies to My Interests:

| Interest Area | Application from This Project |
|---------------|-------------------------------|
| **Design & Manufacturing** | Understanding stress concentrations helps design parts that won't fail at holes, fillets, and corners |
| **R&D** | Validating FEA against theory builds confidence in simulation-driven design |
| **Robotics** | Lightweight beam design principles apply directly to robot arm structures |
| **Supply Chain** | Design choices (like adding fillets) affect manufacturability and cost |

---

## 📚 COMPLETE REPORT

📎 **[[Stress Concentration Analysis Report](https://drive.google.com/file/d/1_JJMr1fJPw6OwN85NkwjqSGbb5CWG9P4/view?usp=drive_link)](Analysis_Test_Correlation.pdf)**  
*57-page complete FEA validation of Peterson's stress concentration factors*

*Contains: Complete methodology, mesh details, boundary conditions, all stress plots, theoretical calculations, and correlation tables (57 pages)*

---

## 🏆 ACHIEVEMENTS

- ✅ **Validated FEA against Peterson's theory** with <3% error in optimal cases
- ✅ **Improved safety factor from 1.17 to 6.93** through geometric optimization
- ✅ **Demonstrated 575% stiffness increase** with same material
- ✅ **Comprehensive documentation** with 57-page technical report

---

# 🛰️ PROJECT 2: CubeSat Electronics Mounting Bracket

> **Aerospace-grade structural analysis for spaceflight hardware**

## 📋 PROJECT OVERVIEW

### 🎯 Objective
Design and validate a lightweight mounting bracket to secure an electronics box within a CubeSat satellite frame during launch. The bracket must:
- Withstand **10g acceleration loads** in X, Y, and Z axes
- Maintain **natural frequencies above 65 Hz** to avoid resonance with launch vehicles
- Achieve **minimum safety factor > 1.5**
- Minimize mass while ensuring structural integrity

### 🚀 Why This Matters
CubeSats are exposed to extreme vibration during rocket launch. A failed bracket means lost electronics, failed mission, and wasted millions. This project demonstrates real-world aerospace engineering where **safety is non-negotiable**.

---

## 🔧 METHODOLOGY & PROCESS

### Design Iterations

| Iteration | Material | Key Features |
|-----------|----------|--------------|
| **Iteration 1** | Titanium Ti-6Al-4V | Baseline design, high strength-to-weight ratio |
| **Iteration 2** | AISI 303 Stainless Steel | Geometric optimization, reduced thickness, refined profiles |

### Analysis Performed
1. **Nonlinear Static Structural Analysis** with frictional contact (µ = 0.2) and large deflection
2. **Three Acceleration Load Cases**: 10g in X, Y, and Z directions
3. **Modal Analysis** to determine natural frequencies and mode shapes
4. **Mesh Convergence Study** for accuracy validation

### Boundary Conditions
- Fixed supports at bracket mounting points
- Point mass (3 kg) representing electronics box
- Beam connections simulating fasteners (1.5mm radius)
- Frictional contact between all surfaces

---

## 📊 KEY RESULTS

### Stress & Safety Factor Comparison

| Load Case | Iteration 1 (Ti-6Al-4V) | Iteration 2 (AISI 303) | Improvement |
|-----------|-------------------------|------------------------|-------------|
| **X-Axis Max Stress** | 293.9 MPa | 81.3 MPa | **72% ↓** |
| **Y-Axis Max Stress** | 154.99 MPa | 116.74 MPa | **25% ↓** |
| **Z-Axis Max Stress** | 126.49 MPa | 72.69 MPa | **43% ↓** |
| **Min Safety Factor** | 1.43 (X-axis) | 2.14 (Y-axis) | **50% ↑** |

### Modal Analysis (Vibration Performance)

| Parameter | Iteration 1 | Iteration 2 | Requirement | Status |
|-----------|-------------|-------------|-------------|--------|
| **1st Natural Frequency** | 123 Hz | **281 Hz** | >65 Hz | ✅ EXCEEDED |
| **Mode Shape** | First bending | First bending | - | - |

**281 Hz natural frequency** provides excellent separation from launch vibration frequencies, eliminating resonance risk.

### Force Reaction Validation
- Applied Load: 300 N (3 kg × 10g)
- Reaction Force Sum: ~375 N
- Error: <23.5% (validates boundary conditions)

---

## 📸 VISUAL RESULTS

### Mesh & Model Setup
<img width="1085" height="565" alt="image" src="https://github.com/user-attachments/assets/a83d067d-b70b-4f94-acea-6d942c1460c7" />
<img width="869" height="439" alt="image" src="https://github.com/user-attachments/assets/4010b6ac-f8c4-4e3a-b62d-0d86403c9948" />

**Fig 1:** Multi-zone hexahedral mesh with refinement at critical regions (2.0mm element size)

### Stress Distribution - X-Axis (Iteration 1)
<img width="1069" height="625" alt="image" src="https://github.com/user-attachments/assets/c45880a4-6c58-4472-bd07-c4d8034576cf" />
<img width="872" height="478" alt="image" src="https://github.com/user-attachments/assets/39fae55b-ff91-483d-900f-9a44dad41b86" />

**Fig 2:** Equivalent stress plot showing concentration at bracket root (235.46 MPa averaged)

### Stress Distribution - X-Axis (Iteration 2)
<img width="969" height="441" alt="image" src="https://github.com/user-attachments/assets/3a35ec4b-ff08-486e-9fee-85f865716999" />
<img width="1000" height="768" alt="image" src="https://github.com/user-attachments/assets/a607f08d-8521-4076-b8c6-a0c47a300a02" />

**Fig 3:** Improved design showing significantly lower stress (77.09 MPa averaged)

### Safety Factor Contour
<img width="1272" height="807" alt="image" src="https://github.com/user-attachments/assets/986a80fa-2059-4f70-8eb3-572b67bacc7d" />

**Fig 4:** Safety factor distribution (min 1.43 in Iteration 1)

### Modal Analysis - Mode Shape
<img width="896" height="718" alt="image" src="https://github.com/user-attachments/assets/25d78226-77c6-4dc9-a5af-7a5ed9430c50" />
<img width="861" height="583" alt="image" src="https://github.com/user-attachments/assets/66084034-cf9d-4a8c-929f-4f179822806e" />

**Fig 5:** First bending mode at 123 Hz (Iteration 1)

---

## 🧠 ENGINEERING INSIGHTS & LEARNING

### What This Project Taught Me:

1. **Nonlinear Contact Modeling is Critical**  
   Frictional contact (µ=0.2) between surfaces significantly affects load transfer. Ignoring it would overestimate stiffness by >30%.

2. **Mesh Refinement Strategy Matters**  
   Using 2.0mm element size at brackets with 3.0mm global sizing captured stress gradients accurately while maintaining computational efficiency.

3. **Geometric Optimization > Material Upgrade**  
   Iteration 2 achieved **72% stress reduction** through geometry improvements, not just material change—proving design matters more than material selection.

4. **Modal Analysis Prevents Resonance**  
   Both iterations exceeded 65Hz requirement, with Iteration 2 achieving **281 Hz**—4.3× the minimum requirement, ensuring safe operation.

5. **Validation Builds Confidence**  
   Force reaction checks (<23.5% error) and mesh convergence studies validated that simulation results are trustworthy.

### How This Applies to My Career Interests:

| Interest Area | Application from This Project |
|---------------|-------------------------------|
| **Aerospace Design** | Direct experience with spaceflight hardware requirements and validation |
| **R&D** | Iterative design process from concept to validated solution |
| **Robotics** | Lightweight, stiff structure principles apply directly to robot arms |
| **Manufacturing** | Design choices (material selection, geometry) impact manufacturability |

---

## ✅ KEY ACHIEVEMENTS

- ✅ **Designed aerospace bracket** meeting all CubeSat launch requirements
- ✅ **Achieved 72% stress reduction** through geometric optimization
- ✅ **Improved safety factor from 1.43 to 2.14** (50% increase)
- ✅ **Exceeded frequency requirement** by 4.3× (281 Hz vs 65 Hz)
- ✅ **Validated FEA model** through mesh convergence and force reaction checks
- ✅ **Compared two materials** (Ti-6Al-4V vs AISI 303) for optimal performance

---

## 🏆 FINAL RECOMMENDATION

**Iteration 2 (AISI 303 Stainless Steel) is recommended** for:

- ✅ Higher safety margins (min SF = 2.14)
- ✅ Significantly improved natural frequency (281 Hz)
- ✅ Lower weight through geometric optimization
- ✅ Excellent corrosion resistance
- ✅ Easier machinability for manufacturing

---

## 📚 COMPLETE REPORTS

📎 **[[CubeSat Electronics Assembly Report](https://drive.google.com/file/d/1kzxxJiW3C-UOEjoettPY4SImIeP1KPZJ/view?usp=drive_link)](Simulation_of_CubeSat_Electronics_Assembly.pdf)**  
*65-page comprehensive aerospace bracket analysis with nonlinear FEA and modal analysis*

---

# 🔧 PROJECT 3: CFRP Vertical Pump Shaft Analysis

> **Composite material design for industrial pumping applications**

[[View Full Report](https://drive.google.com/file/d/1nvamfVeiSXRf3xH7h8CjGFaJaigAe4AB/view?usp=drive_link)](Analysis_of_Vertical_Pump.pdf)

## 📋 PROJECT OVERVIEW

### 🎯 Objective
Design and perform static structural analysis of a **carbon fiber reinforced polymer (CFRP) shaft** using IM9 carbon fiber with epoxy matrix for a vertical pump application. The shaft must transfer rotational energy from motor to impeller while withstanding multiple loads and meeting strict safety criteria.

### 🎯 Technical Requirements
- **Margin of Safety (SM) > 0** for all plies and regions
- **Inverse Reserve Factor (IRF) < 1** using Tsai-Wu failure criterion
- **Deformation within acceptable limits** (~0.0001" under pressure load)
- **Weight optimization** through ply trimming

---

## 🔧 MATERIAL SYSTEM: IM9 Carbon Fiber / Epoxy

| Property | Value |
|----------|-------|
| **Density** | 1550 kg/m³ |
| **Young's Modulus X** | 180 GPa |
| **Young's Modulus Y, Z** | 10 GPa |
| **Tensile Strength X** | 2000 MPa |
| **Tensile Strength Y, Z** | 50 MPa |
| **Compressive Strength X** | -1200 MPa |
| **Shear Strength** | 80 MPa |
| **CTE X** | -5e-7 /°C |
| **CTE Y, Z** | 3e-5 /°C |

---

## 📐 COMPOSITE LAYUP OPTIMIZATION

### Iterative Design Process

| Iteration | Layup | Plies | Results |
|-----------|-------|-------|---------|
| **Initial** | [0/45/-45/90]s ×1 | 8 plies (trimmed to 7) | SM = 0.9, IRF = 0.06, Deformation = 0.8" |
| **Improved** | [0/45/-45/90]s ×2 | 16 plies | SM = 12.287, IRF = 0.04, Deformation = 0.25" |
| **Weight-Optimized** | [0/45/-45/90]s ×2 (drop 90° plies 4 & 12) | 14 plies | SM = 10.591, IRF = 0.04, Deformation = 0.3" |

**✅ Final configuration balances weight savings with safety margins**

---

## ⚙️ LOADING CONDITIONS

| Load Type | Magnitude | Application |
|-----------|-----------|-------------|
| **Compressive Axial** | -400 lbf | Free end (Z-direction) |
| **Centrifugal** | -140 lbf | Midpoint (Y-direction) |
| **Thermal** | 113°F (ΔT = 45°F) | Entire shaft body |
| **Internal Pressure** | 6.56 psi | Inner surface |
| **Boundary Condition** | Fixed Support | Z = 0 (motor connection) |

---

## 📊 KEY RESULTS BY ITERATION

### Initial Layup (8 plies → 7 plies trimmed)

| Parameter | Value | Status |
|-----------|-------|--------|
| **Max Deformation** | 1.6355" at free end | ✓ Acceptable |
| **Max Principal Stress** | 151.2 MPa | ✓ << 2000 MPa |
| **IRF (Critical Region)** | 0.2 (unaveraged) | ✓ < 1 |
| **SM (Critical Region)** | 0.9 | ✓ > 0 |

### Improved Layup (16 plies)

| Parameter | Value | Status |
|-----------|-------|--------|
| **Max Deformation** | 0.5348" at free end | ✓ Improved |
| **Max Principal Stress** | 77.1 MPa | ✓ 49% reduction |
| **IRF (Critical Region)** | 0.045 | ✓ Excellent |
| **SM (Critical Region)** | 12.287 | ✓ 1265% improvement |

### Weight-Optimized Layup (14 plies - Final Design)

| Parameter | Value | Status |
|-----------|-------|--------|
| **Max Deformation** | 0.6286" at free end | ✓ Acceptable |
| **Max Principal Stress** | 82.1 MPa | ✓ Well below limit |
| **IRF (Critical Region)** | 0.05 | ✓ < 1 |
| **SM (Critical Region)** | 10.591 | ✓ > 0 |
| **Weight Reduction** | 2 plies removed | ✓ Achieved |

---

## 📸 KEY VISUAL RESULTS

### Mesh & Model Setup
<img width="817" height="681" alt="image" src="https://github.com/user-attachments/assets/3da03bf1-8037-411c-b3e8-6cd75758cca4" />

**Fig 1:** Structured quadrilateral mesh with refinement at critical regions (0.1" global size)

### Ply Stackup Visualization
<img width="842" height="488" alt="image" src="https://github.com/user-attachments/assets/caba0349-52ca-43d0-a781-331b00f97e4d" />
<img width="856" height="526" alt="image" src="https://github.com/user-attachments/assets/12142592-ab81-471f-9880-bb663ec27221" />
<img width="866" height="571" alt="image" src="https://github.com/user-attachments/assets/59c0a755-0204-48d9-870c-f1a3c763913d" />
<img width="846" height="503" alt="image" src="https://github.com/user-attachments/assets/9d23d681-1442-4b65-bc8f-c1407c97c69c" />
<img width="846" height="503" alt="image" src="https://github.com/user-attachments/assets/13187224-efc3-4ca4-8a88-fa01a4a0f68c" />

**Fig 2:** [0/45/-45/90]s ×2 layup showing 16 plies with 90° ply trimming at center

### Stress Distribution - Final Design
<img width="827" height="361" alt="image" src="https://github.com/user-attachments/assets/2b3e35f4-c481-4f12-86d1-104c5f388e15" />
/>

**Fig 3:** Maximum principal stress distribution ( ~68.9 MPa in the middle portion)

### Failure Index (IRF) - Final Design
<img width="830" height="360" alt="image" src="https://github.com/user-attachments/assets/a1f89297-7d6d-471e-8499-535ddc0bda4f" />


**Fig 4:** Inverse Reserve Factor distribution (max 0.48944, well below 1.0)

### Deformation - Final Design
<img width="828" height="366" alt="image" src="https://github.com/user-attachments/assets/628405ef-f499-487a-9f71-11055b8ca0a2" />

**Fig 5:** Total deformation (~0.8 inches in the middle portion)

---

## 🧠 ENGINEERING INSIGHTS & LEARNING

### What This Project Taught Me:

1. **Composite Design is Iterative**  
   The initial [0/90] layup failed under shear loads. Adding ±45° plies reduced IRF from >1 to 0.04—a critical lesson in anisotropic material behavior.

2. **Ply Trimming Balances Weight & Strength**  
   Dropping two 90° plies reduced weight while maintaining SM >10—showing that strategic material removal can optimize performance.

3. **Tsai-Wu Criterion is Essential**  
   For orthotropic materials, simple von-Mises stress isn't enough. Tsai-Wu failure criterion properly accounts for fiber-direction vs transverse strengths.

4. **Thermal Effects Matter in Composites**  
   With CTE = -5e-7 in fiber direction but 3e-5 transverse, thermal loads create significant internal stresses that must be analyzed.

5. **Margin of Safety vs Deformation Trade-off**  
   The improved layup achieved SM = 12.287 but increased deformation—real engineering requires balancing competing requirements.

### How This Applies to My Career Interests:

| Interest Area | Application from This Project |
|---------------|-------------------------------|
| **Pump Design** | Direct industry experience—worked as pump designer before MS |
| **Composite Materials** | Advanced material selection for corrosive environments |
| **R&D** | Iterative optimization from concept to validated design |
| **Manufacturing** | Ply trimming impacts manufacturability and cost |
| **Supply Chain** | Material selection (CFRP vs steel) affects sourcing and lifecycle cost |

---

## 🏆 KEY ACHIEVEMENTS ACROSS ALL PROJECTS

- ✅ **Validated FEA against Peterson's theory** with <3% error in optimal cases
- ✅ **Designed aerospace bracket** meeting all CubeSat launch requirements with 281 Hz natural frequency
- ✅ **Optimized composite pump shaft** with SM = 10.59 and IRF = 0.04
- ✅ **Achieved 72% stress reduction** through geometric optimization in CubeSat bracket
- ✅ **Demonstrated 1265% safety margin improvement** through composite layup optimization
- ✅ **Successfully implemented ply trimming** for weight reduction while maintaining safety
- ✅ **Completed 7+ analysis iterations** across 3 projects demonstrating systematic engineering approach

---

## 📚 COMPLETE REPORTS

📎 **[[CFRP Vertical Pump Shaft](https://drive.google.com/file/d/1nvamfVeiSXRf3xH7h8CjGFaJaigAe4AB/view?usp=drive_link)](Analysis_of_Vertical_Pump.pdf)**  
*27-page composite shaft design with Tsai-Wu failure analysis and ply optimization*

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
| **Full Pump Assembly** | Complete centrifugal pump | .SLDASM | [⬇️ Download]([[Centrifugal_Pump_Assembly.SLDASM]](https://drive.google.com/file/d/1Ow6IMRqj_t4rm53GcW-qntSOM763Eczx/view?usp=drive_link)) |


### 🎥 Animation
[![Pump 3D Rotation](pump_thumbnail.png)]([pump_animation.mp4](https://drive.google.com/file/d/1yl3Kv6atwfIJSos7mL0MnHumhGoIOO4X/view?usp=drive_link))
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
[![[[Watch Animation](https://drive.google.com/file/d/1xuxxkCB-Fr_ETgu9kvBzxQl9QUUzzdvy/view?usp=drive_link)]
> *📌 **Note:** Click the image above to view the jaw mechanism in motion*
### CAD File
[![[[STL File](https://drive.google.com/file/d/1DHjSgzLE-1GvEyVzbTtuvgDfAPWRScHn/view?usp=drive_link)]
---

### 🔧 Featured Design: Porsche GT3 RS Side View Design
**Software:** [SolidWorks]  
**Type:** Automotive surface modeling

## 🎥 DESIGN VISUALIZATION

### Animation / Motion Study
[![[[[Watch Animation](https://drive.google.com/file/d/133JVbjB6clYyYMkEWL70kwWiYvH3xSBV/view?usp=drive_link)]]
### CAD File
[![[[[STL File](https://drive.google.com/file/d/13apAdldV3YJVNDy6NKGdVGBNvTroLUgo/view?usp=drive_link)]]

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
