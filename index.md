---
title: Manoa Pulse
---

# Manoa Pulse

### By Oscar Tio, Sebastian Wheelehan, Nathan Wong

---

## Overview

### Problem
Students often struggle to find available spaces on campus for studying, eating, or meeting. Popular locations such as libraries, dining areas, and study lounges can become overcrowded, leading to wasted time and frustration. Currently, there is no centralized way for students to check how busy a location is before going there.

### Solution
**Manoa Pulse** is a web-based platform that allows students to view and share real-time crowd levels at various locations across the University of Hawaiʻi at Mānoa campus. By combining user-submitted updates with aggregated data, the system provides a live estimate of how busy a place is, helping students make better decisions about where to go.

---

## Approach

To use Manoa Pulse, users first create an account and log in.

### Browse Locations
Users can view a list of popular campus locations such as libraries, dining halls, and study areas.

### Check Busyness Levels
Each location displays a current **busyness status**:
- Low
- Medium
- High  

Based on recent user input.

### Submit Updates
Users at a location can:
- Report how busy it is  
- Optionally include comments or photos  

### View Trends
Users can see patterns of busyness over time, helping them predict peak hours.

---

## Mockup Page Ideas

### Landing Page
- Overview of popular locations  
- Quick indicators of current busyness levels  

### Location List Page
- List of all tracked campus locations  
- Color-coded indicators:
  - 🟢 Low  
  - 🟡 Medium  
  - 🔴 High  

### Location Detail Page
- Current busyness level  
- Recent user updates  
- Historical trends (charts/graphs)  

### Submit Update Page
- Form to report busyness  
- Optional comment field  

### User Profile Page
- History of submitted updates  
- Contribution activity  

---

## Use Case Example

1. A student wants to study and checks Manoa Pulse  
2. They see the main library is crowded  
3. Another study space shows low occupancy  
4. The student goes there instead  
5. They submit an update  
6. Other students benefit in real time  

---

## Beyond the Basics

### Real-Time Updates
- Live updates using polling or WebSockets  

### Heat Map Visualization
- Campus map showing crowded areas  

### Prediction System
- Use historical data to predict busy times  

### Notifications
- Alerts when locations become less crowded  

### Sensor Integration (Optional)
- Use Wi-Fi/device counts for occupancy estimates  

### Gamification
- Reward users for contributing updates  

---

## Project Goals

- Reduce time wasted searching for space  
- Improve campus efficiency  
- Provide real-time, community-driven insights  

---

## Current Status

- Initial concept defined  
- Mockups in progress  
- Core features planned  

---

## Future Work

- Implement backend (API + database)  
- Build frontend interface  
- Deploy and test with real users  

---
