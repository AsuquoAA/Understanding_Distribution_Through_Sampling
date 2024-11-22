# Understanding Distribution Through Sampling

## Overview

This project demonstrates the concept of distribution through sampling using animations in Python. We explore various random distributions and their characteristics by incrementally sampling from them and visualizing the results dynamically.
This project:

---

## Project Description

1. Utilizes four common distributions:
 - Normal Distribution
 - Gamma Distribution
 - Exponential Distribution
 - Uniform Distribution
2. Creates a dynamic animation where samples (between 100 and 1000) are drawn iteratively from each distribution.
3. Visualizes the sampled distributions in a 2x2 subplot layout with their respective density histograms.
4. Features enhancements like fixed axis limits, clean visuals without axis clutter, and annotations to show sample counts.
Bonus: Uses Matplotlib's animation module to save the animation as an MP4 file.

--

## Features
1. Dynamic Animation: Animates sampling from four random distributions.
2. Clean Visualization: Subplots share styling, with removed axis ticks and spines for a cleaner look.
3. Parameter Adjustment: The project is easily extensible to add widgets for parameterizing the distributions.
4. Export to Video: Saves the animation as an MP4 file using the ffmpeg writer.

---

## Setup and Installation

Ensure the following libraries are installed:
1. matplotlib
2. numpy
3. ipywidgets
4. ffmpeg
- code: pip install matplotlib numpy ipywidgets  
For ffmpeg, install it via your package manager or from the official FFmpeg website.

---

## How to run this project

1. Clone the Repository:
- code: git clone https://github.com/Lazycodes/Understanding-Distribution-Sampling.git
 
2. Navigating to directory
- code: cd Understanding-Distribution-Sampling

---

## Results and Observations
The animations reveal how increasing the sample size leads to the histograms better approximating the theoretical density curves for each distribution:
  - Normal Distribution: Symmetrical, bell-shaped curve emerges.
  - Gamma Distribution: Positive skew becomes apparent.
  - Exponential Distribution: High initial probability, tapering off gradually.
  - Uniform Distribution: Flat density curve across the range.
Example of final output
