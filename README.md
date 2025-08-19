# 🚴 Delivery Route Optimization using TSP & VRP  

## 📌 Overview  
This project demonstrates how **route optimization** can improve delivery efficiency for a logistics/food delivery company.  
We implement **Traveling Salesman Problem (TSP)** and **Vehicle Routing Problem (VRP)** on real Bengaluru road networks using **Python, OR-Tools, and OSMnx**.  

Key objectives:  
- Optimize delivery routes to **minimize travel distance & time**.  
- Compare **single rider (TSP)** vs **multiple riders (VRP)**.  
- Visualize optimized routes on **real road networks** using Folium maps.  

---

## ⚙️ Tech Stack  
- **Python Libraries**:  
  - `OR-Tools` – for solving TSP & VRP.  
  - `OSMnx` & `NetworkX` – to fetch and compute real road networks.  
  - `Folium` – for interactive map visualizations.  
  - `Pandas`, `NumPy`, `Matplotlib` – for data processing & analysis.  

---

## 📊 Project Workflow  

### 1️⃣ Synthetic Dataset (TSP on Random Points)  
- Generated random delivery points.  
- Solved TSP to find the shortest possible delivery path for a **single rider**.  
- Visualized the optimized route using Folium.  

### 2️⃣ Real Road Network (Bengaluru)  
- Collected actual Bengaluru street network using **OSMnx**.  
- Simulated deliveries from a restaurant (depot) to multiple customers.  
- Solved TSP using **road-based shortest paths**.  
- Visualized optimized routes on a real city map.  

### 3️⃣ Vehicle Routing Problem (VRP with Multiple Riders)  
- Extended optimization to **multiple riders (vehicles)**.  
- Balanced routes by splitting customers between 2–3 riders.  
- Visualized rider-specific delivery routes with different colors.  

---

## 📷 Visualizations  
- Optimized **TSP route** for a single rider.  
- **VRP routes** for 2–3 riders, drawn along **actual Bengaluru streets**.  
  

---

## ✅ Results & Conclusion  
- **TSP (Single Rider)** works but is inefficient for real businesses.  
- **VRP (Multiple Riders)** reduces travel distance per rider, improves speed, and lowers CO₂ emissions.  
- Demonstrated how delivery companies (e.g., Swiggy/Zomato/Logistics firms) can optimize routes using AI & Graph theory.  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/delivery-optimization.git
   cd delivery-optimization
   ```
2. Install Dependencies

   ```bash
   pip install -r requirements.txt```

3. Open Jupyter Notebook

   ```bash
   jupyter notebook```

## ✨ Future Improvements  

- ⏰ **Add time windows** – deliveries must be made within specific time slots.  
- 🚦 **Incorporate traffic conditions** – optimize dynamically based on real-time traffic.  
- 📈 **Scale to larger datasets** – handle 100+ delivery points efficiently.  
- 📊 **Build a dashboard (Streamlit/React)** – simulate and visualize orders in real-time.  


## Screenshots of Output:

1. Without using actual Roads (just straight lines)
<img width="393" height="405" alt="image" src="https://github.com/user-attachments/assets/55fd6a36-3ebd-4873-8ff9-b79b97dc2748" />

2. Distance Heat Matrix (Banglore Road Network)
<img width="393" height="405" alt="image" src="https://github.com/user-attachments/assets/9106f048-0d41-4680-a17c-4cda586e99cc" />

3. Using Actual Road Network -TSP
<img width="393" height="405" alt="image" src="https://github.com/user-attachments/assets/b95f6028-30dc-4587-8e8b-464c24fb20f6" />

4. Using Actual Road Network - VRP (2 riders)
   <img width="417" height="350" alt="image" src="https://github.com/user-attachments/assets/de164a2d-5850-46b0-8609-34eb44919341" />

5. Using Actual Road Network - VRP (3 riders)
   <img width="439" height="382" alt="image" src="https://github.com/user-attachments/assets/938b2120-dab2-49db-8dee-2360921ba0ec" />

---
## 🏁 Conclusion  

This project demonstrated how delivery route optimization can be solved using **TSP (single rider)** and **VRP (multiple riders)** on real road networks.  
By applying these techniques, delivery companies can achieve:  

- Faster and more efficient deliveries  
- Reduced fuel costs and rider fatigue  
- Lower environmental impact  

The approach provides a foundation that can be extended with advanced features like time windows, traffic conditions, and real-time simulations.  
---
__made by arjun7579__


