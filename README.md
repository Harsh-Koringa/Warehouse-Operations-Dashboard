# Warehouse Operations Dashboard (Power BI + Python)

This project simulates and visualizes complete warehouse operations for an AgriTech supply chain startup.  
It includes automated stock computation, warehouse capacity analysis, and a smart recommendation engine that suggests the best warehouse for each incoming farmer load based on capacity, SKU compatibility, and nearest factory distance.

## 🚀 Features
- **Python Engine for Stock & Capacity Calculation**  
  - Computes real-time warehouse utilization using initial stock + inbound/outbound movements  
  - Generates warehouse free capacity, alerts, and readiness scores  

- **Warehouse Recommendation System**  
  - Recommends the most optimal warehouse for each incoming load  
  - Logic based on distance to preferred factory, available capacity, and SKU compatibility  
  - Flags high-risk loads (warehouse nearing full capacity)

- **Interactive Power BI Dashboard**
  - Warehouse overview (capacity, utilization, top 5 filled warehouses)
  - Incoming goods with recommended warehouse & capacity-risk highlights
  - Stock movement timeline (inbound vs outbound over time)
  - SKU distribution and factory-warehouse distance visualization

## 📂 Tech Used
- **Python** (Pandas, Numpy) for data processing  
- **Power BI** for analytics dashboard  
- **CSV datasets** (auto-generated simulation)

## 📈 Deliverables
- Complete Power BI `.pbix` dashboard  
- Python scripts for stock logic and recommendation  
- Clean CSV datasets  
- PDF export of dashboard  
