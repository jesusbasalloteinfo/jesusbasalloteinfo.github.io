---
layout: default
title: Lunaris: Lunar Astronomical Calculator
subtitle: Jesús Basallote Gallardo
---

# Lunaris: Lunar Astronomical Calculator

**Lunaris** is an astronomical tool developed in **C++** that accurately calculates various parameters related to the **Moon**. It features an efficient and clear graphical interface, using **wxWidgets**.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/1CWGZZO.png" alt="Lunaris Logo" width="100"/>
  <figcaption><em>Figure 1: Application Logo</em></figcaption>
</figure>


It is part of a suite of astronomical programs that also includes:
- **HelioMetrica**, focused on solar analysis.
- **PlanexiScope**, dedicated to planetary ephemerides.

Currently, Lunaris is only available for Windows and is under active [development](./) (Link coming soon...).


## Main Features 

Lunaris is a lightweight and accurate tool for amateur astronomers who need detailed lunar information. It offers several functionalities, organized into tabs, that allow users to obtain detailed and up-to-date information about Earth's natural satellite.

Its development in C++ ensures speed and efficiency, while its modular design allows for future expansion or integration with other programs in the suite.

Below are the main screens of the application, illustrated with screenshots.

## Main Menu and Small Lunar Visualizer

Lunaris features a **Small Lunar Visualizer** at the top of the interface that allows users to see at first glance how is the Moon looking, its current ilumination and its visibility

<figure style="text-align: center;">
  <img src="https://i.imgur.com/b9eBuZF.png" alt="Main menu and Small Lunar Visualizer" width="400"/>
  <figcaption><em>Figure 2: Main menu and Small Lunar Visualizer</em></figcaption>
</figure>

It also includes Time-Coordinates input and time speed control where:

- Auto: Gets the current time and starts moving forward
- Stop: Stops time
- Play: Starts the time added at normal speed (Must have used Add before)
- Play x4: Starts the time added at 4 times speed (Must have used Add before)
- Add: Configures time to be what has been introduced on the input zone
- Get Actual Time: Gets the current time and configures it to be used

## 1. Moon Position

This tab shows the Moon's current position in **equatorial coordinates** (Right Ascension and Declination), along with other relevant data such as:
- Distance from Earth  
- Angular Diameter
- Moon Horizontal Parallax

This allows users to locate the Moon in the sky at any given time.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/HwrqK4o.png" alt="Moon Position" width="400"/>
  <figcaption><em>Figure 3: Lunar Position Calculation Screen</em></figcaption>
</figure>

## 2. Moon Phase

This tab provides information on the **current lunar phase**, expressed both as text (e.g., "First Quarter") and as a percentage of visible illumination, among other information like the **current lunar age** or **Brown lunation**.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/Zgs5W3i.png" alt="Moon Phase" width="400"/>
  <figcaption><em>Figure 4: Lunar Phase Calculation Screen</em></figcaption>
</figure>

### Phase Viewer

<figure style="text-align: center;">
  <img src="https://i.imgur.com/0OjrW7s.png" alt="Moon Viewer" width="400"/>
  <figcaption><em>Figure 5: Lunar Phase Visualizer Screen</em></figcaption>
</figure>

Within a button in the parent screen, a **graphical phase viewer** displays how the Moon appears from Earth at the current moment with some customization for:

- Changing how the Moon is shown
- Enabling/disabling stars
- Showing or hiding the lunar terminator
- Enabling/disabling Dynamic Sky (Shows the Moon with a realistic sky depending on the location and the time of the day)
- Enabling or disabling some information on the visualizer with custom fonts and colors

It also features a button to save an image directly from the visualizer.


## 3. Moonrise and Moonset

This tab shows the **Moonrise and Moonset times** based on the observer's location. 

<figure style="text-align: center;">
  <img src="https://i.imgur.com/zzTicOF.png" alt="Moonrise and Moonset" width="400"/>
  <figcaption><em>Figure 6: Moonrise and Moonset Calculation Screen</em></figcaption>
</figure>

## 4. Next New Moon and Full Moon

Here, users can find the exact dates and times of the upcoming:

- **New Moon**
- **Full Moon**

This is especially useful for planning astronomical observations, lunar studies, or simply for skywatching enthusiasts.

<figure style="text-align: center;">
  <img src="https://i.imgur.com/XnCoL0W.png" alt="New and Full Moon" width="400"/>
  <figcaption><em>Figure 7: Next New Moon and Full Moon Calculation Screen</em></figcaption>
</figure>

[Go Back](./)
