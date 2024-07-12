# WildlifeAI
WildlifeAI is an Autonomous Wildlife Monitoring System designed for safari parks and zoos. It leverages AI techniques including object detection, sound analysis, and graph-based movement tracking to detect, classify, and analyze wildlife activities in real-time.

## Key Features
- **Object Detection:** Utilizes Haar-like features and YOLOv8 for accurate and real-time animal detection in images and video.
- **Sound Analysis:** Classifies animal moods (e.g., Angry, Normal) based on audio amplitude, with proposed enhancements for accuracy using multimodal data.
- **Graph-Based Movement Tracking:** Models animal movements in their habitat using graph theory, predicting paths based on behavioral patterns.

## Approach
### Object Detection
Initially employing Haar-like features for preliminary detection, the system transitions to YOLOv8 for enhanced accuracy and real-time capabilities.

### Sound Analysis
Analyzing audio signals for mood classification (Angry, Normal, Sad) based on amplitude, with plans to integrate video analysis for improved accuracy.

### Graph-Based Movement Tracking
Representing wildlife habitat as a graph, nodes depict key locations (e.g., water sources, dens), with edges indicating possible paths. Utilizes BFS for real-time shortest path calculation, with future plans for behavior-driven path identification.

## Limitations and Proposed Solutions
- **Object Detection:** YOLOv8 occasionally misclassifies species; proposed solutions include comprehensive dataset training and clear image provisioning.
- **Sound Analysis:** Heavy dependency on amplitude; proposed solution integrates video feed for enhanced classification accuracy.
- **Movement Tracking:** Currently relies on shortest path; future enhancements aim to identify frequently traveled paths based on observed behavior.

## Future Enhancements
- Incorporate machine learning for adaptive learning from wildlife behavior over time.
- Integrate environmental variables (e.g., seasonality, human impacts) into movement tracking models.

## License
This project is licensed under the [MIT License]
