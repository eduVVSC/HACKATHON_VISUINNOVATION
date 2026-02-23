# Drone Control System – Hackathon Visuinnovation Project



The hackathon had the duration of 3 months, from august until final of november, in which we had constant contact with Visuinnovation to develop an application.

The main goal was to develop a comprehensive **autonomous drone control and monitoring system** built in Python, designed for **waypoint-based navigation** to delivery missions, this system offers automated flight, real-time monitoring, safety validation, weather integration, and detailed logging.

In order to develop it, we needed to strength our knowledge in:
- **Validation of technical requirements**,
- **Drone system, flight and components**, 
- **Database management** **(CRUD)**,
- **API usage**,
- **Embeeded Systems**,
- **Waypoint and locaiton management**,
- **Log creation**,

Before the delivery, in which we got to test it with the drone, we were making the test through a drone simulator (arducopter) sending the personalized instructions via ardupilot controls, same ones received by the drone were going to use in the final demonstration. 

Objective achieved on the simulator:
- Make the **drone fly between multiple points** making **landings** in all of them and **returning to home**,
- **Writing logs** of position during the flight,
- **Refreshing the database** for the **management of users, waypoints and drones**,
- **Safety checks before/during the flyight**,

---

## Core Functionality
- **Autonomous Flight** – Fully automated flight from takeoff to landing
- **Real-Time Monitoring** – Telemetry, battery, and environmental condition tracking
- **Weather Integration** – Live weather data with flight safety assessments
- **Safety Management** – Pre-flight and in-flight parameter checks
- **Mission Management** – Waypoint-based flight planning and execution
- **Dual Logging** – Simple and detailed flight record logs
- **Database Integration** – User and waypoint data managed via Supabase

---

## Technologies Used

- **Python**
- **OpenWeatherMap API** – Real-time weather updates
- **Supabase** – Cloud DB for users and waypoints
- **MAVLink** – Industry-standard drone communication protocol

---

## Key Features

### ✈️ Flight Control
- Automated takeoff and landing
- Waypoint navigation
- Return-to-launch (RTL)
- Live GPS tracking

### 🛡️ Safety System
- Pre-flight checks
- In-flight parameter monitoring
- Weather analysis
- Battery and altitude limits

### 📊 Monitoring & Logging
- Telemetry data recording
- Dual-mode logging (simple & detailed)
- GPS and mission status tracking

### 🌦️ Weather Integration
- Live data: temperature, humidity, wind, visibility
- Condition-based flight approval

### 🗃️ Database Management
- User & waypoint CRUD operations
- Mission planning and record-keeping



### 🧭 Flight Process
1. **Pre-flight Checks** – Validates weather, battery, and safety limits
2. **Mission Planning** – Loads waypoints and calculates route
3. **Takeoff** – Launch sequence initiated
4. **Navigation** – Autonomous flight to destination
5. **Return** – Drone returns to base
6. **Landing** – Final automated descent---

---

## Division of labour

 - Backend -> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Eduardo Vasconcelos](https://github.com/eduVVSC) &nbsp;&nbsp;&nbsp;&nbsp; [Christofer Mota](https://github.com/cde-paiv)  &nbsp;&nbsp;&nbsp;&nbsp; [Joao Vitor Ribeiro](https://github.com/jvrs2002)
 - Frontend -> &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;[Matheus Infingardi](https://github.com/matheusinfingardi) &nbsp;&nbsp;&nbsp;&nbsp; [Davi Montaño](https://github.com/Daviddm03) 
 - Project Manager -> &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Matheus Infingardi](https://github.com/matheusinfingardi)
 - Connection backend and frontend -> [Eduardo Vasconcelos](https://github.com/eduVVSC)
