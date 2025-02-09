# Finite Element Method (FEM) - Slope Stability Analysis

## 📖 Overview
This project performs **Finite Element Method (FEM) analysis** for a **mine bench slope** using real-world displacement and stress data from a CSV file. The analysis identifies **failure zones** using the **Mohr-Coulomb failure criterion**.

### 🔍 **What This Code Does**
✅ Reads input data (`FEM4_data.csv`) containing:
   - **Node coordinates (`X, Y`)**  
   - **Displacements (`u_x, u_y`)**  
   - **Final positions (`X1, Y1`)**  
   - **Stress values (`sigma_xx, sigma_yy, sigma_xy`)**  
   - **Failure status (`Status`)**  

✅ Visualizes:
1. **Displacement Field** (movement vectors of nodes)
2. **Stress Distribution (`sigma_xx`, `sigma_yy`)**
3. **Mohr-Coulomb Failure Zones** (Elastic vs. Failure regions)

---

## 📂 **Dataset Description**
The CSV file `FEM4_data.csv` contains the following columns:

| Column | Description |
|--------|------------|
| `X, Y` | Initial coordinates of the node |
| `u_x, u_y` | Displacement in x and y directions |
| `X1, Y1` | Final coordinates after displacement |
| `sigma_xx, sigma_yy` | Normal stresses in x and y directions |
| `sigma_xy` | Shear stress |
| `Status` | Indicates if the point is **Elastic** or in **Failure** |

---

## 🚀 **Installation & Usage**
### **1️⃣ Install Dependencies**
Ensure Python and the required libraries are installed:
```sh
pip install numpy pandas matplotlib
