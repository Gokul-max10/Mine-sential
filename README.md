MineSentinel AI  
**AI-Powered Robotic Rescue-Support System for Underground Mine Safety**

Problem
Rescue teams entering collapsed mines face:
- Unknown geometry  
- Hazardous gases & fire  
- Poor visibility & communication loss  
- Risk of sending humans into unsafe zones  

Solution
A **low-cost robotic scout** that enters hazardous areas first, gathers data, and provides rescue teams with **situational awareness**.

Core Features
- **Mapping:** LiDAR + SLAM for 2D/3D mine maps  
- **Hazard Monitoring:** Gas sensors, temperature, humidity  
- **Obstacle Analysis:** Detect rubble, classify routes (Passable / Uncertain / Blocked)  
- **Worker Localization:** Emergency beacon signals + thermal/camera detection  
- **AI Fusion:** Combine sensor data → risk assessment  
- **Rescue Dashboard:** Live map, hazards, possible worker locations, robot health  

Worker Beacon
- ESP32 + LoRa  
- SOS button + periodic ID transmission  
- Last-known location shown on rescue map
  
Development Stages
- **V1:** Basic robot (mapping + navigation)  
- **V2:** Hazard monitoring (gas, temperature)  
- **V3:** Worker detection (camera + beacon)  
- **V4:** AI fusion + rescue dashboard  
- **V5:** Swarm expansion (multi-robot cooperation)
  
Limitations
- Underground communication reliability  
- Sensor interference (dust, smoke, water)  
- GPS unavailable underground  
- Prototype not certified for real mine deployment  

Innovation / USP
Unlike existing mine robots, **MineSentinel AI integrates**:  
- Mapping + hazard monitoring  
- Obstacle passability analysis  
- Worker emergency localization  
- Multi-modal survivor detection  
- AI risk prioritization  
- Human-in-the-loop rescue support
  
Approximate Cost (Prototype)
₹35,000 – ₹60,000 depending on sensor choices  
