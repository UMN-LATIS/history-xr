---
title: Virtual Fort Snelling
permalink: /projects/virtual-fort-snelling
image: /assets/img/virtual-fort-snelling/commanders-house-2021-cropped.png
---


# Virtual Fort Snelling <span class="badge badge-gray">beta</span>

![commanders house](/assets/img/virtual-fort-snelling/commanders-house-2021.png)

<br/>

## About

The goal of this project is to allow users to see the site of Fort Snelling at Bdote as it looked in many different periods. Although this historic site has been Dakota homeland for thousands of years, and was an active-use settler colonial military site for 125 years, visitors today mainly see the reconstructed 1820s frontier fort. This 3D landscape model is being created using digital elevation models, historic maps and photographs, archaeological remains, oral histories, and archived documents.

<br/>

## People

- Faculty project lead: [Dr. Katherine Hayes](https://cla.umn.edu/about/directory/profile/kathayes){:target="_blank"}
- Programmer: [Dan Shervheim](https://danielshervheim.com){:target="_blank"}

<br/>

## Status

This project is under construction. Beta releases are available below for a variety of platforms. Please understand that this is a work-in-progress. There might be bugs, and content/features are subject to change.

<br/>

## Downloads

**macOS Beta Releases**


- <span class="badge badge-blue">Nov 23rd, 2021</span> [Google Drive](https://drive.google.com/file/d/18YGPeIK_Ba_XedxMY4uGEfwa9WsMk_Vt/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">Nov 19th, 2021</span> [Google Drive](https://drive.google.com/file/d/1imO9MbcdZ3dVaj3RBTC874-D_BDYnwGO/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">Nov 8th, 2021</span> [Google Drive](https://drive.google.com/file/d/1jajtiGJtGuTASSVLAwFgyhZRCtBRbn8j/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">v1.2</span> [Google Drive](https://drive.google.com/file/d/1FQJMOL-Riitxqau2lPNtAl27oI1ZcmR5/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">v1.1</span> [Google Drive](https://drive.google.com/file/d/1mjJrSPAXbWI6WrEXQhKjKin_5s7Z3EP7/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">v1.0</span> [Google Drive](https://drive.google.com/file/d/1jwzM2dRhmhLbjkLbQuiTCPIqu6kTDd8c/view?usp=sharing){:target="_blank"}

**Windows Beta Releases**

- <span class="badge badge-blue">Nov 23rd, 2021</span> [Google Drive](https://drive.google.com/file/d/1h-gtJ89j_EYoze6PFlbyTltn5mVQqAaV/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">Nov 19th, 2021</span> [Google Drive](https://drive.google.com/file/d/1I6-pHRmsMo0G2EbmfRK5J6fobt5IfjEo/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">Nov 8th, 2021</span> [Google Drive](https://drive.google.com/file/d/19nZoKCIjU77vqF42c4auFpr91R7TTTZh/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">v1.2</span> [Google Drive](https://drive.google.com/file/d/1ATOEzaz_anJ1eNBS7Lz3KUWpsiYuTyLZ/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">v1.1</span> [Google Drive](https://drive.google.com/file/d/1mfNAqyDsjYkFihs2QJ4XqV0AuRxAOnjn/view?usp=sharing){:target="_blank"}
- <span class="badge badge-gray">v1.0</span> [Google Drive](https://drive.google.com/file/d/19zgNdxXbUTcmxIre9TFKjgmfJvcVF58o/view){:target="_blank"}

<!--

 **Web Beta Releases**

- <span class="badge badge-gray">v1.0</span> [HistoryXR](/projects/virtual-fort-snelling/player){:target="_blank"}

-->

<br/>

## Feedback

Found a bug? Want to share some feedback? Please let us know via email!

<a href="mailto:aisos@umn.edu?subject=Virtual Fort Snelling Feedback">Contact Us</a>

<br/>


## Version History

Here's what's new.

---

### November 23rd, 2021

<span class="badge badge-blue">Features</span>
- Added clouds to the sky.
- Added manually-placed trees to certain parts of the diamond area for certain time periods.
- Added anti-aliasing options to the Graphics menu.

<span class="badge badge-green">Fixes</span>
- Updated the tree coverage to better reflect the post-glacial period of the last few thousands years.
- Prevented users from being able to walk off the edge of the map.
- Fixed a scrolling-sensitivity issue on Windows.

---

### November 19th, 2021

<span class="badge badge-blue">Features</span>
- Added finer control over the application performance via the Graphics menu page.
    - Now you can toggle on/off grass, plants, trees, water reflections, and particle effects.
- Added a steamboat model, and railroad bridge models.
- Added native wildflowers to the landscape.

<span class="badge badge-green">Fixes</span>
- Improved the rendering of the tooltips.

<span class="badge badge-red">Known Bugs</span>
- The tree coverage currently only covers the pre-glacial period.

<span class="badge badge-gray">Upcoming</span>
- Add clouds to the sky.
- Add props (wagons, barrels, etc) and more smoke particle systems to the chimneys.
- Improve the vegetation coverage / make it responsive over time.

---

### November 12th, 2021

<span class="badge badge-blue">Features</span>
- Improved the camera controls.
    - Now you can move with WASD/Arrow Keys
- Added rivers.
- Added an option to enable/disable reflections in the river surfaces.
    - Enabled looks much better, but comes at a performance cost.
- Added preliminary vegetation.
- Added in-world tooltips that one can click on to launch certain pages.

<span class="badge badge-green">Fixes</span>
- Fixed color inconsistancy in the UI.

<span class="badge badge-gray">Upcoming</span>
- Improve the vegetation coverage / make it responsive over time.
- Road 3D models
- Refine tooltip UI / interaction.

---

### November 8th, 2021

<span class="badge badge-blue">Features</span>
- Reworked the internal data model to allow for [community contributions](http://umn-latis.github.io/virtual-fort-snelling-documentation/) via [Github](https://github.com/UMN-LATIS/virtual-fort-snelling-data).
- Reworked the timeline UI.
- Reworked the internal rendering setup to prepare for vegetation.

<span class="badge badge-green">Fixes</span>
- Upgraded to Unity 2020.3 LTS and the Universal Render Pipeline
    - Improved overall stability and performance.

<span class="badge badge-red">Known Bugs</span>
- Some text and icons are blurry on non-retina screens.
- Scrolling is not sensitive enough on Windows platforms.
- Minor color inconsistencies in the UI.

<span class="badge badge-gray">Upcoming</span>
- Vegetation (trees, grass, etc) 3D models
- Road 3D models
- Tour tooltips in-world (in addition to in-UI).

---

### v1.2

March 31st, 2021

<span class="badge badge-blue">Features</span>
- Small screen support
    - The interface now automatically resizes from devices as small phones to as large as desktops.
    - This is in preparation for a mobile release.
- Birds eye view
    - You can now view the fort from a “birds eye” view in addition to a “first person” view.
    - Look for the toggle in the pause menu.
        - Left click + drag to move in birds eye view.
        - Right click + drag to pivot the camera in birds eye view.
        - Scroll with the mouse wheel to zoom in birds eye view.
- Timeline scrolling
    - Now you can just scroll through the timeline to change the year, rather than having to click on individual years.
- Virtual MISLS link
    - The menu page for “building 103” now links to the Virtual MISLS app through our HistoryXR website.

<span class="badge badge-green">Fixes</span>
-  Upgraded to Unity 2019.4 LTS
    - Improved overall stability.

<span class="badge badge-red">Known Bugs</span>
- Some icons are blurry on non-retina screens.
- Some buttons are too small on non-retina screens.
- Touchpad scrolling is sometimes jittery on macOS platforms.
- In birds eye view, building block the player from moving. They shouldn't.

---

### v1.1

November 29, 2020

<span class="badge badge-blue">Features</span>
- Added click-and-draggable scrollbars to menus.

<span class="badge badge-green">Fixes</span>
- Adjusted menu scrolling sensitivity on desktop platforms.

---

## v1.0

November 21, 2020

- Initial release.

<br/>