---
date: 2021-06-04 01:00:00
layout: post
title: Performance Points
subtitle: Datenshi Performance Points tables
description: This is our formulas for the pp calculations
image: https://cdn.discordapp.com/attachments/728581754398572546/850180235093606450/datenshi_pp.png
category: osu
author: troke12
paginate: false
---
## Explanation

We are having of much questions about the calculation works, because datenshi it's providing the custom calculation that make we more different, this calculation are still 10:11 with official bancho but there are some modifications that we make, please see below

## PP Rate per Drain Time

Our system scales PP gain based on map's drain length. It decreases PP gain for super short maps (low capped at 30 seconds). On the other side, any long maps gain a permanent buff as well.

### PP Penalty Graph

<iframe src="https://www.desmos.com/calculator/qhnxmnor3p?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

### PP Penalty Formulas

![image](https://user-images.githubusercontent.com/10250068/120732868-9daa4200-c518-11eb-8643-ec3db6094cd8.png)

### PP Penalty Mapping Table

| ![image](https://user-images.githubusercontent.com/10250068/120732997-e4983780-c518-11eb-837b-0b79b2a5a7e6.png) | ![image](https://user-images.githubusercontent.com/10250068/120733021-f11c9000-c518-11eb-8f84-1f108f14ad07.png) | ![image](https://user-images.githubusercontent.com/10250068/120733060-fed21580-c518-11eb-89b6-24a5f8e18758.png) |
|---|---|---|
| 30 | 10 | 90 |
| 35 | 18.75 | 81.25 |
| 40 | 30 | 70 |
| 45 | 43.75 | 56.25 |
| 50 | 60 | 40 |
| 55 | 78.75 | 21.25 |
| 60 | 100 | 0

### PP Buff Graph

<iframe src="https://www.desmos.com/calculator/pnzwphb8y7?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

### PP Buff Mapping Table

| ![image](https://user-images.githubusercontent.com/10250068/120732997-e4983780-c518-11eb-837b-0b79b2a5a7e6.png) | ![image](https://user-images.githubusercontent.com/10250068/120733021-f11c9000-c518-11eb-8f84-1f108f14ad07.png) |
|---|---|
| 180 | 100 |
| 240 | 100 |
| 300 | 100 |
| 450 | 105 |
| 600 | 110 |
| 900 | 113 |
| 1200 | 116 |
| 1500 | 119 |
| 1800 | 122 |
| 2400 | 124 |
| 3000 | 126 |
| 3600 | 128 |
| 5400 | 134 |
| 7200 | 140 |

## Taiko PP

Our system use an extra approach to calculate PP on Taiko. We check how hard to comprehend the pattern either with very low or very high scroll speed, this also affected by mod usage as well.

## Mania PP

We gave extra buff on mania in NC and DT
