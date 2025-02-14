# **Bus Simulator README**

## **1. Available Policy Files**  
The following policy files provide different bus scheduling control strategies:  

- **`visnc`** → No control (**worst case, high bunching**)  
- **`visfc`** → Forward headway control (**simple control, ~100 bunching**)  
- **`visTD3_Distill`** → Our MARL control method (**best case, ~10 bunching**)  
- **`visDDPG_Distill`** → Our advanced method (**almost no bunching**)  

---

## **2. Bus Simulator Policy File Usage Guide**  
This guide provides step-by-step instructions on how to use a **policy `.zip` file** to simulate bus operations in the **Bus Simulator**.

### **Step 1: Download the ZIP File**  
Ensure you have the required **`.zip` policy file** downloaded to your local device.

### **Step 2: Upload the Policy File to the Simulator**  
1. Open the **Bus Simulator**: [**https://bus-holding-control-simulator.vercel.app/**] 
2. Click **"Upload Model Output"** on the interface.  
3. Select the downloaded **`.zip` file** from your local storage.  
4. Click **"Upload"** to proceed.  

### **Step 3: Select and Start the Simulation**  
1. After uploading, click **"Select Model Output"** and choose the **policy file** you just uploaded.  
2. Click **"Start Simulation"** to begin running the model.  
3. Adjust the **simulation speed** as needed (**1x, 10x, 50x, or 100x**).  

### **Step 4: Interactive Simulation Features**  
During the simulation, you can:  
- **Adjust progress manually** → Drag the timeline slider to jump to any point in the simulation.  
- **Control playback** → Use **Reset / Pause / Start** at any time.  

---

## **3. Bus Simulator Interface Features**  

### **3.1 Left-Side Control Panel**
The **left-side panel** provides various functionalities:  

- **Minimal Mode** → Toggle between a **3D map** view or a **single-route visualization**.  
- **Simulation Statistics** *(automatically displayed after selecting a policy file)*:  
  - **Total number of buses**  
  - **Total number of bus stops**  
  - **Key performance metrics**:  
    - **Avg Waiting Time**  
    - **Avg Bus Travel Time**  
    - **Avg Dwelling Time**  
    - **Avg Bus Occupancy**  
    - **Total Service Time**  
    - **Total Number of Bunching**  
- **Custom Passenger Capacity** → Users can modify the **capacity** setting.  
- **Live Operational Data** → Dynamically updates based on real-time bus movements:  
  - **Next bus arrival time**  
  - **Number of dispatched buses**  
  - **Number of buses currently on the road**  

### **3.2 Map View Options**  
The simulator supports **three different viewpoints** for better visualization:  
- **Top View** → Overhead perspective for a **global comparison of routes**.  
- **Rotated View** → Switch between **South-side** and **North-side perspectives** for **enhanced 3D visualization**.  

---

**Now you are ready to explore bus operations with the Bus Simulator!**
