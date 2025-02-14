Bus Simulator README
1️⃣ Available Policy Files
The following policy files provide different bus scheduling control strategies:

visnc → No control (worst case, high bunching)
visfc → Forward headway control (simple control, ~100 bunching)
visTD3_Distill → Our MARL control method (best case, ~10 bunching)
visDDPG_Distill → Our advanced method (almost no bunching)
2️⃣ Bus Simulator Policy File Usage Guide
This guide provides step-by-step instructions on how to use a policy .zip file to simulate bus operations in the Bus Simulator.

📥 Step 1: Download the ZIP File
Ensure you have the required .zip policy file downloaded to your local device.

🖥 Step 2: Upload the Policy File to the Simulator
Open the Bus Simulator: Click Here
Click "Upload Model Output" on the interface.
Select the downloaded .zip file from your local storage.
Click "Upload" to proceed.
📂 Step 3: Select and Start the Simulation
After uploading, click "Select Model Output" and choose the policy file you just uploaded.
Click "Start Simulation" to begin running the model.
Adjust the simulation speed as needed (1x, 10x, 50x, or 100x).
🎛 Step 4: Interactive Simulation Features
During the simulation, you can:
✅ Adjust progress manually → Drag the timeline slider to jump to any point in the simulation.
✅ Control playback → Use Reset / Pause / Start at any time.

3️⃣ Bus Simulator Interface Features
📌 Left-Side Control Panel
The left-side panel provides various functionalities:

🔹 Minimal Mode → Toggle between a 3D map view or a single-route visualization.
🔹 Simulation Statistics (automatically displayed after selecting a policy file):
🚍 Total number of buses
🚏 Total number of bus stops
📊 Key performance metrics:
⏳ Avg Waiting Time
🚍 Avg Bus Travel Time
🏠 Avg Dwelling Time
🚌 Avg Bus Occupancy
⏱ Total Service Time
⚠ Total Number of Bunching
🔹 Custom Passenger Capacity → Users can modify the capacity setting.
🔹 Live Operational Data → Dynamically updates based on real-time bus movements:
⏳ Next bus arrival time
🚌 Number of dispatched buses
🛣 Number of buses currently on the road
🗺 Step 5: Map View Options
The simulator supports three different viewpoints for better visualization:

🔝 Top View → Overhead perspective for a global comparison of routes.
🔄 Rotated View → Switch between South-side and North-side perspectives for enhanced 3D visualization.
