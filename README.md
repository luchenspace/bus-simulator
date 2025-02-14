# bus-simulator policy file instruction
1. visnc: no control (worst case, many bunching);  
2. visfc: forward headway control (simple control, ~100 bunching);  
3. visTD3_Distill: our marl control method (best case, ~10 bunching);  
4. visDDPG_Distill: our method, which should be almost no bunching

# Bus Simulator Policy File Usage Guide
This guide provides step-by-step instructions on how to use a policy .zip file to simulate bus operations in the Bus Simulator.

# Step 1: Download the ZIP File
Ensure you have the required .zip policy file downloaded to your local device.

# Step 2: Upload the Policy File to the Simulator
5. Open the Bus Simulator: [https://bus-holding-control-simulator.vercel.app/]
6. Click "Upload Model Output" on the interface.
7. Select the downloaded .zip file from your local storage.
8. Click "Upload" to proceed.

# Step 3: Select and Start the Simulation
9. After uploading, click "Select Model Output" and choose the policy file you just uploaded.
10. Click "Start Simulation" to begin running the model.
11. Adjust the simulation speed as needed (1x, 10x, 50x, or 100x).

# Step 4: Interactive Simulation Features
During the simulation, you can:
12. Adjust progress manually → Drag the timeline slider to jump to any point in the simulation.
13. Control playback → Use Reset / Pause / Start at any time.

# Step 5: Left-Side Control Panel Features
The left-side panel provides various functionalities:
- Minimal Mode → Toggle between a 3D map view or a single-route visualization.
- Simulation Statistics (automatically displayed after selecting a policy):
	1. Total number of buses
	2. Total number of bus stops
	3. Static performance metrics:
		1. Avg Waiting Time
		2. Avg Bus Travel Time
		3. Avg Dwelling Time
		4. Avg Bus Occupancy
		5. Total Service Time
		6. Total Number of Bunching
- Custom Passenger Capacity → Users can modify the capacity setting as needed.
- Live Operational Data → Dynamically updates based on bus movements:
	1. Next bus arrival time
	2. Number of dispatched buses
	3. Number of buses currently on the road

# Step 6: Map View Options
The simulator supports three different viewpoints for better visualization:
- Top View → Overhead view for a global comparison of routes.
- Rotated View → Switch between South-side and North-side perspectives for enhanced 3D visualization.
