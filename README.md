In the face of increasing urbanization and the frequent occurrence of large public gatherings, crowd safety and efficient space management have become critical. This project presents a real-time web-based crowd monitoring and control system that visualizes live heatmaps of crowd density and suggests dynamic escape routes in case of emergencies.

Utilizing live video feeds from CCTV, ESP32-CAMs, or thermal cameras, the system leverages AI-based computer vision models (e.g., YOLO or OpenCV) to detect and count individuals in defined zones. These data points are transmitted via MQTT to a FastAPI backend, which processes and updates crowd density information. The frontend, built with React.js, displays an intuitive interface showing real-time heatmaps over a floor plan, crowd count analytics, and optimized escape routes using pathfinding algorithms like A*.

The system includes overload detection alerts for administrators and can adapt in real time to blocked or crowded exits. Designed for auditoriums, campuses, malls, and other public infrastructures, this solution enhances emergency preparedness and spatial awareness by combining IoT, computer vision, and real-time web technologies.

