---
layout: default
title: PlanexiScope: Planetary Ephemeris Tool
---

# PlanexiScope: Planetary Ephemeris Tool

**PlanexiScope** is an astronomical tool developed in **C++** designed to compute and visualize detailed planetary data. It features an efficient and clear graphical interface, using **wxWidgets**.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/VXmKETs.png" alt="PlanexiScope Logo" width="100"/>
  <figcaption><em>Figure 1: Application Logo</em></figcaption>
</figure>

It is part of a suite of astronomical programs that also includes:
- **Lunaris**, focused on lunar data.
- **HelioMetrica**, focused on solar analysis.

Currently, PlanexiScope is only available for Windows and is under active [development](./) (Link coming soon...).



## Main Menu and Planet Selector

PlanexiScope features a **planet selector** at the top of the interface that allows users to choose any of the major planets in the Solar System. Once selected, all displayed data and visualizations update in real-time according to the chosen body.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/HTsOXQI.png" alt="Main menu and Planet Selector" width="400"/>
  <figcaption><em>Figure 2: Main menu and Planet Selector</em></figcaption>
</figure>

It also includes Time-Coordinates input and time speed control where:

- Auto: Gets the current time and starts moving forward
- Stop: Stops time
- Play: Starts the time added at normal speed (Must have used Add before)
- Play x4: Starts the time added at 4 times speed (Must have used Add before)
- Add: Configures time to be what has been introduced on the input zone
- Get Actual Time: Gets the current time and configures it to be used

## 1. Planet-Earth Position

This section displays the **geocentric position** of the selected planet, using **equatorial coordinates** (Right Ascension and Declination), as seen from Earth, along with other relevant data such as:
- Distance to Earth
- Angular Diameter

<figure style="text-align: center;">
  <img src="https://i.imgur.com/x54WVGL.png" alt="Planet-Earth Position" width="400"/>
  <figcaption><em>Figure 3: Planet-Earth Position Screen</em></figcaption>
</figure>


## 2. Planet-Sun Position

This tab shows the **heliocentric position** of the selected planet with respect to the Sun, including:
- Distance to the Sun
- Angular Diameter

<figure style="text-align: center;">
  <img src="https://i.imgur.com/odZ4hYD.png" alt="Planet-Sun Position" width="400"/>
  <figcaption><em>Figure 4: Planet-Sun Position Screen</em></figcaption>
</figure>

## 3. Rise and Set Times

Based on the user's location, this section calculates  **rise and Set times** of the selected planet, along with current visibility status with is visible on the main menu.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/tuDXFJ6.png" alt="Rise and Set Times" width="400"/>
  <figcaption><em>Figure 5: Rise and Set Calculation Screen</em></figcaption>
</figure>


## 4. Perihelion and Aphelion

Displays the dates and distances for the next:
- **Perihelion** (closest approach to the Sun)
- **Aphelion** (farthest distance from the Sun)

These calculations are especially useful for understanding orbital dynamics and brightness variations of planets.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/f4vgqv1.png" alt="Perihelion and Aphelion" width="400"/>
  <figcaption><em>Figure 6: Perihelion and Aphelion Data</em></figcaption>
</figure>

## 5. Visualizer

Accessible from the main menu, the **Visualizer** is a planetary orbit viewer. It allows users to:

- Display the **full Solar System** or focus on:
  - **Inner Solar System**
  - **Outer Solar System**
  - The **selected planet**
- Enable/disable planetary **names and labels**
- Export high-quality **images** of the orbit view

More examples can be found [here](https://imgur.com/a/planexiscope-KjE8DNP).
<figure style="text-align: center;">
  <img src="https://i.imgur.com/ZYcxGY4.png" alt="Orbit Visualizer" width="400"/>
  <figcaption><em>Figure 7: Planetary Orbit Visualizer</em></figcaption>
</figure>


[Go Back](./)

