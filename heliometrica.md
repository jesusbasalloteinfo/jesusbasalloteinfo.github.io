---
layout: default
title: HelioMetrica: Solar Data Analyser
subtitle: Jesús Basallote Gallardo
---

# HelioMetrica: Solar Data Analyser

**HelioMetrica** is an astronomical tool developed in **C++** that provides precise solar data and visualizations for amateur astronomers. It features a clean graphical interface built using **wxWidgets**.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/TGgmk0f.png" alt="HelioMetrica Logo" width="100"/>
  <figcaption><em>Figure 1: Application Logo</em></figcaption>
</figure>

It is part of a suite of astronomical programs that also includes:
- **Lunaris**, focused on lunar data.
- **PlanexiScope**, dedicated to planetary ephemerides.

Currently, HelioMetrica is only available for Windows and is under active [development](./) (Link coming soon...).

## Main Features

HelioMetrica offers a compact and effective interface to explore solar data. It includes several core functionalities accessible through tabs and menus, allowing detailed exploration of the Sun’s position, rise/set times, seasonal events, and a real-time sky visualizer.

Its development in C++ ensures fast performance and high accuracy, with a modular design for future feature expansions or integration with other programs in the suite.

Below are the main screens of the application, illustrated with screenshots.

## Main Menu and Small Solar Visualizer

HelioMetrica features a **Small Solar Visualizer** at the top of the interface that allows users to see at first glance how is the Sun looking and its visibility

<figure style="text-align: center;">
  <img src="https://i.imgur.com/q675gIi.png" alt="Main menu and Small Solar Visualizer" width="400"/>
  <figcaption><em>Figure 2: Main menu and Small Solar Visualizer</em></figcaption>
</figure>

It also includes Time-Coordinates input and time speed control where:

- Auto: Gets the current time and starts moving forward
- Stop: Stops time
- Play: Starts the time added at normal speed (Must have used Add before)
- Play x4: Starts the time added at 4 times speed (Must have used Add before)
- Add: Configures time to be what has been introduced on the input zone
- Get Actual Time: Gets the current time and configures it to be used

## 1. Sun Position

This tab provides the Sun’s current position in **equatorial coordinates** (Right Ascension and Declination), along with key parameters like:
- Distance from Earth
- Angular Diameter


<figure style="text-align: center;">
  <img src="https://i.imgur.com/EhHsfhj.png" alt="Sun Position" width="400"/>
  <figcaption><em>Figure 2: Solar Position Calculation Screen</em></figcaption>
</figure>


## 2. Sunrise and Sunset

This tab calculates the times of **sunrise and sunset** and the day-night lenght for the user's location, taking into account refraction and atmospheric effects.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/hwF5myF.png" alt="Sunrise and Sunset" width="400"/>
  <figcaption><em>Figure 3: Sunrise and Sunset Calculation Screen</em></figcaption>
</figure>


## 3. Equinox and Solstice

Here, users can see the exact times of the year's major solar events:
- **March Equinox**
- **June Solstice**
- **September Equinox**
- **December Solstice**

<figure style="text-align: center;">
  <img src="https://i.imgur.com/TRe5zDp.png" alt="Equinox and Solstice" width="400"/>
  <figcaption><em>Figure 4: Equinox and Solstice Dates</em></figcaption>
</figure>


## 4. Visualizer

Accessible from the main menu, this visualizer provides a **real-time solar sky simulation**, allowing the user to visualize:

- Enabling/disabling stars
- Enabling/disabling Dynamic Sky (Shows the Sun with a realistic sky depending on the location and the time of the day)
- Enabling or disabling some information on the visualizer with custom fonts and colors

It also features a button to save an image directly from the visualizer.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/cIsskua.png" alt="Solar Visualizer" width="400"/>
  <figcaption><em>Figure 5: Real-Time Solar Visualizer with Dynamic Sky enabled</em></figcaption>
</figure>

[Go Back](./)
