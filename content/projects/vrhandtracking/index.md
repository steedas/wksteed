---
title: "Characterizing VR Headset Performance with Cobots"
date: 2024-08-23
draft: true
summary: "Using a KUKA cobot as a tool for designing repeatable hand-tracking experiments"
tags: ["welcome", "new", "about", "first"]
---

This summer I was lucky to work as a research assistant at [Ingenuity Labs Research Institute](https://ingenuitylabs.queensu.ca/) apart of [MITHRIL](https://mithrilab.com/). My coworker Eric and I characterised the hand-tracking accuracy of the [Meta Quest Pro](https://www.meta.com/ca/quest/quest-pro/) and [Meta Quest 3](https://www.meta.com/ca/quest/quest-3/) using a [KUKA LBR iiwa R7 robotic manipulator](https://www.kuka.com/-/media/kuka-downloads/imported/8350ff3ca11642998dbdc81dcc2ed44c/0000246832_en.pdf?rev=d1e0fd2b524b42b295c7c1d392315ad1&hash=CF9C0E57E85DA17685B1EA67075ACF45) as a proxy for a human hand/arm. Our results showed landmark tracking accuracy on the order of ~1.12 cm for the Quest Pro and ~1.73cm for the Quest 3, which are some of the highest accuracy results for any measured virtual reality headset. The technology is getting really good.

{{<youtube YZOw3LcU0GM>}}
_Our third test is designed to see how long it takes for motion from the hand to be displayed in the headset lenses. This delay is measured by counting the number of frames between when the robot passes a certain point (the blue ring around the end effector turns on) and the lens detects the robot at that point (the VR headset lens changes color from blue to purple)_


