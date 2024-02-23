---
layout: default
title: Planing
parent: Road
grand_parent: RoadBuilder
nav_order: 1
---

# Road Planning
---

Click **Road** tab and **Plan** button to activate road plan mode.

## Creating a simple road

- **Right click** multiple times in the viewport to create a serial of control points.
![](001.gif)

## Dragging control point

- **Left click** control point to select it, you can drag it or type in precise coordinates in property editor.
![](002.gif)

## Curvature

- You can adjust the curvature of each control point, and control the curvature gradient via the CurvatureBlend parameter.
![](003.gif)

{: .note }
Variable curvature is generally used for the transition from straight roads to curved roads. CurvatureBlend parameter controls the ratio of variable curvature to fixed curvature, with 0 representing the entire section of road being fixed curvature, 1 representing the entire section of road being variable curvature, and 0.5 being half each.

## Road style

- Choose appropriate road style before creating roads.
![](004.gif)

- You can also create custom road styles by clicking the **Create** button.

## Base height

- You can adjust base height of the road before creating it.
![](005.gif)