# SC5-Timer

<p align="center">
  <p align="center">Smart Timer for Events</p>
</p>

<h4 align="center">
  <a href="https://sc5countdown.partymc.de">Website</a>
</h4>

<h3 align="center">
</h3>

An intelligent timer for game events with the ability to integrate it into OBS and remove the background using custom CSS.

- OBS integration
- No Google Fonts
- Easily customizable

Please note that this project is still under development.

Check out the demo.

## 📱 Screenshots

<table>
  <tr>
    <td><img alt="SC5 Timer Preview" src="img/2025-01-13_08-10.png"/></td>
   </tr>
</table>

## Overview

This repository contains the source code for a responsive countdown webpage that displays the remaining time until the SC5 Christmas Event. The webpage shows a dynamic countdown in days, hours, minutes, and seconds.

## Features

- Responsive design for various screen sizes (desktop, tablet, mobile)
- Dynamic countdown to a specified date (December 24, 2025, 08:00 AM)
- Animated logo with hover effect
- Full-screen background image
- Semi-transparent countdown box with blur effect
- OBS-compatible CSS file for streaming integration

## Technologies

- HTML5
- CSS3 (with Flexbox and animations)
- JavaScript (Vanilla JS for the countdown)
- Webp image format for optimized loading times

## Repository Structure

- ```/www``` - Contains all webpage files (HTML, images)
- ```/scripts``` - Contains the CSS file for OBS integration
- ```/img``` - Contains preview images and other media

## Installation

1. Clone the repository:
   ```
   git clone https://git.fastm.de/Max/SC5-Timer.git
   ```

2. Open the ```/www/index.html``` file in your preferred web browser.

## OBS Integration

The ```/scripts``` directory contains a special CSS file that can be used to integrate the timer into OBS and properly crop it. Add the webpage as a browser source in OBS and apply the CSS file to display only the timer.

## Customization

### Changing the Countdown Target

To change the target date of the countdown, edit the following line in the ```/www/index.html``` file:

```javascript
const targetDate = new Date('2025-12-24T08:00:00+01:00');
```

### Customizing the Style

The design can be customized by editing the ```<style>``` section in the ```index.html``` file. The webpage uses responsive breakpoints for different screen sizes:

- Desktop: > 768px
- Tablet: 480px - 768px
- Mobile: < 480px

## 📜 License

MIT License

