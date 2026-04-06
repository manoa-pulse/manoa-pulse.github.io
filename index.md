---
layout: essay
type: essay
title: "Manoa Pulse"
date: 2026-03-30
labels:
  - Software Engineering
  - Nextjs
---

By Oscar Tio, Sebastian Wheelehan, Nathan Wong

## Overview

**Problem:**  
Students often struggle to find available spaces on campus for studying, eating, or meeting. Popular locations such as libraries, dining areas, and study lounges can become overcrowded, leading to wasted time and frustration. Currently, there is no centralized way for students to check how busy a location is before going there.

**Solution:**  
Manoa Pulse is a web-based platform that allows students to view and share real-time crowd levels at various locations across the University of Hawaiʻi at Mānoa campus. By combining user-submitted updates with aggregated data, the system provides a live estimate of how busy a place is, helping students make better decisions about where to go.

## Approach

To use Manoa Pulse, users first create an account and log in.

1. **Browse locations**  
   Users can view a list of popular campus locations such as libraries, dining halls, and study areas.

2. **Check busyness levels**  
   Each location displays a current “busyness” status (e.g., low, medium, high) based on recent user input.

3. **Submit updates**  
   Users at a location can:
   - Report how busy it is
   - Optionally include comments or photos

4. **View trends**  
   Users can see patterns of busyness over time, helping them predict peak hours.

## Mockup Page Ideas

- **Landing Page**
  - Overview of popular locations
  - Quick indicators of current busyness levels

- **Location List Page**
  - List of all tracked campus locations
  - Color-coded indicators (green = low, yellow = medium, red = high)

- **Location Detail Page**
  - Current busyness level
  - Recent user updates
  - Historical trends (charts or graphs)

- **Submit Update Page**
  - Form to report how busy a location is
  - Optional comment field

- **User Profile Page**
  - History of submitted updates
  - Contribution activity

## Use Case Ideas

- A student wants to study and checks Manoa Pulse to see if the library is crowded.
- They see that the main library is very busy but another study area has low occupancy.
- The student chooses the less crowded location.
- While there, they submit an update indicating the current busyness level.
- Other students benefit from the updated information in real time.

## Beyond the Basics

- **Real-Time Updates**
  - Live updates using polling or WebSockets

- **Heat Map Visualization**
  - Map of campus showing crowded areas

- **Prediction System**
  - Use historical data to predict busy times

- **Notifications**
  - Alert users when a location becomes less crowded

- **Integration with Sensors (optional)**
  - Use Wi-Fi or device counts to estimate occupancy

- **Gamification**
  - Reward users for contributing accurate updates
