# Shubham J. Sonara - Mechanical Engineering Portfolio

**MS Mechanical Engineering Candidate** | University of New Haven  
📧 shubham.sonara@example.com | 📍 New Haven, CT  
🔗 [LinkedIn](https://linkedin.com/in/shubham-sonara) | 🐙 [GitHub](https://github.com/shubhamsonara159-cloud)

---

## 👨‍🎓 ABOUT ME

I am a **Mechanical Engineering graduate student** at the University of New Haven with a passion for **design, analysis, and optimization** of mechanical systems. My academic journey has equipped me with strong foundations in **Computer Aided Engineering (CAE)** , **Finite Element Analysis (FEA)** , and **Computational Fluid Dynamics (CFD)** .

I thrive at the intersection of **theoretical mechanics** and **practical engineering solutions**. Every project I undertake is driven by curiosity to understand "why" things work and "how" they can be improved.

---

## 🎯 PROFESSIONAL INTERESTS

| Domain | My Focus |
|--------|----------|
| **⚙️ Design & Manufacturing** | Creating efficient, manufacturable designs with optimized performance-to-weight ratios |
| **🔬 R&D & Product Development** | Translating concepts into validated designs through simulation and testing |
| **🤖 Robotics & Automation** | Structural analysis of robotic components, lightweight design for dynamic systems |
| **📦 Supply Chain & Logistics** | Understanding how design decisions impact manufacturing, assembly, and distribution |

---

## 💡 MY ENGINEERING PHILOSOPHY

> *"Good design is invisible. Great design is felt through performance, reliability, and efficiency."*

I believe that successful mechanical engineers don't just analyze components—they understand the **entire ecosystem**: how parts are made, how they fail, how they interact, and how they impact the bigger system. Whether it's a CubeSat bracket surviving launch vibrations or a microchannel cooling a high-heat-flux chip, every detail matters.

---

## 🛠️ TECHNICAL SKILLS

| Category | Skills & Tools |
|----------|----------------|
| **FEA** | Ansys Workbench (Static Structural, Modal, Nonlinear Contact), Mesh Convergence |
| **CFD** | COMSOL Multiphysics (Conjugate Heat Transfer, Laminar Flow) |
| **CAD** | Ansys SpaceClaim, Parametric Modeling |
| **Materials** | Ti-6Al-4V, AISI 303, Al 6061, Steel A36, AISI 1045 |
| **Analysis** | Stress Concentration Factors (Peterson), Thermal Management, Safety Factors |
| **Validation** | Theory-Experiment Correlation, Error Analysis, Mesh Independence Studies |
| **Soft Skills** | Technical Writing, Data Visualization, Project Documentation |

---

## 📂 FEATURED PROJECTS

| # | Project | Description | Tools | Status |
|---|---------|-------------|-------|--------|
| **1** | **Stress Concentration Analysis** | FEA validation of Peterson's Kt factors for plate with hole, cantilever beam, and shoulder fillet | Ansys Static Structural | ✅ Complete |
| **2** | **CubeSat Electronics Bracket** | *(Coming Soon)* Aerospace bracket design for 10g launch survival | Ansys Workbench | 🔄 In Progress |
| **3** | **Microchannel Heat Sink** | *(Coming Soon)* CFD optimization for high-heat-flux electronics cooling | COMSOL Multiphysics | 🔄 In Progress |

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

📎 **[[https://drive.google.com/file/d/1_JJMr1fJPw6OwN85NkwjqSGbb5CWG9P4/view?usp=drive_link](https://drive.google.com/file/d/1_JJMr1fJPw6OwN85NkwjqSGbb5CWG9P4/view?usp=drive_link)]([Analysis_Test_Correlation.pdf](https://drive.google.com/file/d/1_JJMr1fJPw6OwN85NkwjqSGbb5CWG9P4/view?usp=drive_link))**

*Contains: Complete methodology, mesh details, boundary conditions, all stress plots, theoretical calculations, and correlation tables (57 pages)*

---

## 🏆 ACHIEVEMENTS

- ✅ **Validated FEA against Peterson's theory** with <3% error in optimal cases
- ✅ **Improved safety factor from 1.17 to 6.93** through geometric optimization
- ✅ **Demonstrated 575% stiffness increase** with same material
- ✅ **Comprehensive documentation** with 57-page technical report

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
