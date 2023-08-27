slip-calculator

<hr>
Use a free and open source CAD software to explore slip geometry interactively.

Learn about and tweak the four parameters that determine a slip: *width, sanding cylinder diameter, cane diameter, and edge thickness*, and calculate dip, centerline thickness, and stature.

Explore the Froment Rule of Thirds, and calculate cane and cylinder ODs required to yield slips that satisfy this geometric condition.
<hr>

Introduction and Tutorial on Youtube:

<a href="https://youtu.be/wXY4rGBuEL4" target="_blank">
<img src="assets/yt-video-image.png" alt="Video Introduction and Tutorial" width="600"/>
</a>
<hr>

Table of Contents:
[TOC]

# Example Screenshots
## Visualizing and calculating dip, centerline and stature from the four fundamental parameters
<img src="./assets/fourFundamentalParams.png" alt="Tapered rolling mandrel in FreeCAD" width="600"/>

## Exploring the Froment Rule of Thirds
<img src="./assets/fromentRuleOfThirds.png" alt="Tapered rolling mandrel in FreeCAD" width="600"/>

# Capabilities

Using this CAD project, you can do the following:

- calculate dip and centerline from cane OD, cylinder OD, slip width, edge thickness
- calculate the cane OD and cylinder OD required to create a certain dip and centerline, given a width and edge thickness
- calculate cane OD that is required to satisfy the Froment Rule of Thirds for a given sanding cylinder OD and width, and calculate the resulting dip and centerline
- calculate cylinder OD that is required to satisfy the Froment Rule of Thirds for a given cane OD and width, and calculate the resulting dip and centerline
- calculate the cane OD required to produce certain centerline, for a given dip, width (and thus sanding cylinder OD), and edge thickness
- calculate the slip width and centerline for a given dip, cylinder OD, cane OD, and edge thickness

# Known Limitations
- trying to calculate the width required to satisfy the Rule of Thirds for a given cane and cylinder OD doesn't converge in the solver, and erratic results are obtained
