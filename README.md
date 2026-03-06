# Sketch-Based Network Traffic Monitoring and Burst Detection

A prototype system for monitoring streaming network traffic using compact probabilistic data structures and detecting abnormal traffic bursts.

---

## Overview

Modern networks generate massive traffic streams that must be monitored in real time for performance optimization and security monitoring.  
However, storing every packet or flow is computationally expensive and often infeasible at high speeds.

To address this challenge, network measurement systems frequently use **sketch-based data structures**, which allow approximate frequency estimation with extremely low memory usage.

This project demonstrates how a **Count-Min Sketch** can be applied to monitor network traffic flows and detect potential traffic bursts or anomalies.

---

## Key Features

- Simulation of streaming network traffic
- Flow frequency estimation using **Count-Min Sketch**
- Detection of **heavy hitters** (high-frequency flows)
- Burst anomaly detection in traffic streams
- Visualization of traffic patterns

---
