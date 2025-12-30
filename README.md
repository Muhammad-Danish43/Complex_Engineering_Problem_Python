# Complex Engineering Problem (CEP)
## Introduction to AI Programming  
**CityLearn 2022 Dataset – Building 2 Energy Analysis**

---

## 📌 Project Overview
This project addresses a **Complex Engineering Problem (CEP)** using basic Python programming concepts.  
The objective is to analyze **electricity consumption**, **solar photovoltaic (PV) generation**, and **electricity cost** for *Building 2* using the **CityLearn 2022 dataset**.

The solution strictly follows the instructions provided by the instructor and uses only the concepts covered in class.

---

## 📂 Dataset Description
The following CSV files are used in this project:

- **`Building_2.csv`**
  - Contains hourly electricity consumption data
  - Includes solar generation values per kW of installed PV system

- **`pricing.csv`**
  - Contains hourly electricity price data

These files were provided by the instructor as part of the CEP resources.

---

## 🛠️ Tools & Technologies
- **Python (Basic)**
  - Lists
  - Loops
  - Conditional statements
  - File handling
- **Jupyter Notebook**

> ⚠️ No advanced libraries (such as pandas, NumPy, or AI/ML libraries) are used.

---

## 🧮 Methodology
The following steps are performed to solve the CEP:

1. Load the `Building_2.csv` file using basic Python file handling.
2. Extract:
   - Equipment Electric Power as **non-shiftable load**
   - Solar Generation per kW
3. Calculate total electricity consumption.
4. Convert solar generation values to usable energy units.
5. Load electricity prices from `pricing.csv`.
6. Calculate:
   - Electricity bill **without PV**
   - Net electricity consumption **with PV**
7. Separate:
   - Grid electricity consumption
   - Surplus (wasted) energy
8. Interpret results using numerical outputs.

---

## 📊 Key Outcomes
- Solar PV generation reduces the building’s net electricity consumption.
- Electricity cost is lower when solar generation is considered.
- Surplus energy can potentially be stored or exported to the grid.

---

## 📁 Project Structure
📦 Complex_Engineering_Problem
┣ 📜 Complex_Engineering_Problem_Python.ipynb
┣ 📄 Building_2.csv
┣ 📄 pricing.csv
┗ 📄 README.md

---

## ✅ CEP Compliance
✔ Uses **CityLearn 2022 dataset**  
✔ Follows **exact CEP instructions**  
✔ Uses **basic Python only**  
✔ Code is clean, readable, and well-structured  
✔ Suitable for **academic submission**

---

## 👨‍🎓 Author
**Muhammad Ali**  
Bachelor of Engineering  
University of Engineering and Technology, Peshawar  

---

## 📌 Note
This project is completed for academic purposes as part of the *Introduction to AI Programming* course and adheres to all provided guidelines.

