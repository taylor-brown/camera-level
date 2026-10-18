# Camera Level

**Live page: <https://taylor-brown.github.io/camera-level/>**

A free level and angle finder that runs in your phone's browser. No app, no ads, no install. Open the page, allow the camera and motion sensor, and hold the phone sideways.

It shows the live camera picture with a line drawn on top that always hangs straight down (a plumb line), using the phone's tilt sensor. Compare the line with a wall, door frame, picture or shelf to see how far off it is.

## Use it with a laser level

Point the camera at the line from a laser level and compare it with the on-screen plumb line:

- Check whether a laser's vertical line is truly plumb.
- Check a laser level's horizontal line by turning the phone so the on-screen line runs along it.
- Get a quick second opinion on a laser level you suspect has drifted.

The phone's sensor is good to about half a degree, so it is fine for a sanity check but not a replacement for calibrating a laser level against a proper reference.

## Features

- Plumb line that turns green when the phone is level (within 0.5°).
- **Angle**: add a second line at any angle you type in. It glows green and the phone vibrates when the phone's tilt matches, so you can measure or set a slope, a roof pitch or a cut angle.
- **Zero**: calibrate if your phone reads slightly off on a known-level surface.
- **Photo**: save the camera frame with the lines drawn on it.
- Works upright or sideways, in either direction.

## How to use

1. Open the live page on your phone (HTTPS is required for the camera).
2. Tap **Start** and allow camera and motion access (iPhones ask for motion separately).
3. Hold the phone sideways against or in front of what you want to check.

If there is no tilt sensor (for example on a desktop), a slider appears so you can try the screen out.

## Run it yourself

It is one `index.html` with no dependencies and no build step. Put it on any HTTPS host, such as GitHub Pages: Settings, Pages, deploy from the `main` branch.

## Keywords

phone level, camera level, plumb line, laser level, angle finder, inclinometer, clinometer, spirit level, bubble level, web app
