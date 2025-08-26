# 2. Concept Design

## 2.1 Implementation of Mechanical Improvement
### 2.1.1 Torque Analysis
- Rim push: 23 N × 0.3 m = **6.9 Nm**  
- Lever pull: 30 N × 0.41 m = **12.3 Nm**  
Levers provide significant mechanical advantage.

![Torque Graph](../images/fig16_torque_graph.png)

### 2.1.2 New Shaft Design
- **Original shaft**: 12 mm carbon steel, designed for ~100 kg.  
- **New shaft**: Prevents sun gear rotation, transmits torque efficiently.  
- Machined and fitted with a support pin.  

![Machined Shaft](../images/fig19_new_shaft.png)

### 2.1.3 Assembly Relations
CAD assemblies ensured correct fitting of spider, sun, and stacked gears.  

![Assembly](../images/fig24_wheelchair_assembly.png)

### 2.1.4 Mechanical Advantage
Planetary gear system:  
- Sun = 40 teeth  
- Planets = 15 teeth  
- Annular = 70 teeth  

Result: mechanical advantage ~1.6×.

![Gear Ratio](../images/fig33_mech_advantage.png)

---

## 2.2 Creation of a System for Geometry Adaptation
Wheel spokes vary → no ISO standard.  
Used **Grasshopper parametric design** to adapt hub, spokes, and keyways for different geometries.

---

## 2.3 Redesign of PLA Parts
PLA parts failed quickly.  
- Replaced with **nylon** and **metallic gears**.  
- Increased durability, smoother motion.

---

## 2.4 New Dimensions for Structural Integrity
Improved fit and fastening.  
Designed better spoke attachments to prevent displacement.

---

## 2.5 Revisited Lever System
Different lever configurations tested:
- Removable  
- Telescopic  
- Folding  
- Semi-fixed  
- With counterweights for stability
