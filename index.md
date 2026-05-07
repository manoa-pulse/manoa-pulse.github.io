---
title: "Manoa Pulse"
---

# Manoa Pulse

By Oscar Tio, Sebastian Wheelehan, Nathan Wong

---

## Overview

**Problem:**  
Students often struggle to find available spaces on campus for studying, eating, or meeting. Popular locations such as libraries, dining areas, and study lounges can become overcrowded, leading to wasted time and frustration. Currently, there is no centralized way for students to check how busy a location is before going there.

**Solution:**  
Manoa Pulse is a web-based platform that allows students to view and provides near real-time estimates based on recent user-submitted updates at various locations across the University of Hawaiʻi at Mānoa campus. By combining user-submitted updates with aggregated data, the system provides a live estimate of how busy a place is. The platform also includes an interactive campus heat map that visualizes busyness levels using color-coded zones.

---

## Deployment

- Live App: [Manoa Pulse](https://manoa-pulse-one.vercel.app/) [![CI Status](https://github.com/manoa-pulse/manoa-pulse/actions/workflows/ci.yml/badge.svg)](https://github.com/manoa-pulse/manoa-pulse/actions/workflows/ci.yml)
- [GitHub Organization](https://github.com/manoa-pulse)  
- GitHub Pages: [Project Site](https://manoa-pulse.github.io)  


### Current Progress

#### Landing Page
![Landing Page](img/landing-page.png)

#### Pulse Feed
![Pulse Feed](img/pulse-feed-M3.png)

#### Location Page
![Location Page](img/location.png)

#### Specific Location Busyness Details
![Hamilton](img/Hamilton-M3.png)

#### Profile
![Profile](img/profile.png)

#### User Submission
![User Submission](img/user-submission.png)

#### Heatmap
![Heatmap](img/heatmap.png)

#### Admin Panel
![Admin](img/admin.png)

---

## User Guide

1. Create an account and log in  
2. View live busyness levels on the Pulse Feed  
3. Explore the interactive heat map  
4. Click a location for detailed information  
5. Submit updates to contribute data 

---

## Developer Guide
1. Clone the project's Github repository
```bash
git clone https://github.com/manoa-pulse/manoa-pulse
cd manoa-pulse
```

2. Install dependencies
```bash
npm install
```

3. Create postgres db
```bash
createdb manoa_pulse
```

4. Set up .env file
```bash
cp sample.env .env
```
You will need to modify your `AUTH_URL` to point to the URL of your app and add your username, password, and the db name to your `DATABASE_URL`.

5. Set up database
```bash
npx prisma migrate dev
npx prisma generate
npm run seed
```

6. Run web app
```bash
npm run dev
```

---

### Technologies

- Next.js  
- React  
- Prisma  
- PostgreSQL  
- React Bootstrap  

---

## Approach

1. Browse locations  
2. Check busyness levels  
3. Submit updates  
4. View trends  

---

## Mockups

- Landing Page  
- Location List  
- Location Detail  
- Submit Update  
- User Profile  

---

## Development History

### M1

- [M1](https://github.com/orgs/manoa-pulse/projects/1)
- Created GitHub organization  
- Set up GitHub Pages  
- Designed concept  
- Created mockups  

### M2

- [M2](https://github.com/orgs/manoa-pulse/projects/3)
- Create interactive heat map
- Each location has a specific page
- Pulse feed, heat map, & specific location pages pull data from PostgreSQL database
- Submit pulse update has details guiding user on what busyness means

### M3
- [M3](https://github.com/orgs/manoa-pulse/projects/5)
- Made general UI improvements
- Users can upload profile pictures and set a name
- Shows opening and closing hours for each location
- Admin panel shows all submissions & users

---

## Team

- Oscar Tio  
- Sebastian Wheelehan  
- Nathan Wong

---

## Contract

- Team Contract: [Doc](https://docs.google.com/document/d/1CUWs6yDzlybhc3uunBIqt2A8Q4dY5DiEtpM3G6IVEMQ/edit?tab=t.0)
