---
title: Simulating ice damage in ice flow
author: Cyrille Mosbeux
date: 2025-17-03 08:30:00 +0100
categories: [Blogging, ice damage and Semi-Lagrangian transport]
tags: [Semi-Lagrangian transport, ice damage]
pin: true
image:
  path: /Images/AMU_d1int_dt_test_2000-2050.gif
  alt: Simulating ice damage and transport in ice flow
---


Transport processes play a crucial role in natural systems, from the movement of air in the atmosphere to ocean currents and ice flow. To study these processes, scientists use mathematical models that describe how substances move within a fluid. A common approach, called the Eulerian method, focuses on tracking changes at fixed points in space, using equations that include advection—the process by which material is carried along by a flow.

However, advection can introduce challenges in numerical models, particularly when using a common technique called the Finite Element Method. Standard versions of this method can struggle with stability, sometimes leading to unwanted errors or distortions in the results. To address this, researchers have developed different techniques.

One of these is the **Semi-Lagrangian method**, which combines aspects of both Eulerian and Lagrangian perspectives—essentially following particles as they move while still using a fixed Eulerian grid for calculations. The method avoids artificial diffusion and can more accurately track movement in complex flows.

In our recent work, we present an efficient SL algorithm designed to handle transport in three-dimensional and simulate ice damage advection over time in the Amundsen Sea Sector.

Stay tuned to lear more about it! 









