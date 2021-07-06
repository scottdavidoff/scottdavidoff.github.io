---
title: A Visual Analytics Approach to Debugging Cooperative Autonomous Multi Robot Systems Worldviews
date: 2020-10-26T00:00:00-00:00
draft: false
venue: IEEE Conference on Visual Analytics Science and Technology
venue short name: VAST 2020
authors:
- Suyun "Sandra" Bae
- Federico Rossi
- Joshua Vander Hook
- Scott Davidoff
- Kwan-Liu Ma
description: An algorithm and visual encoding to explain unexpected multi-robot system behavior
keywords:
- multi-robot systems
- Human-Subjects Qualitative Studies
- Debugging
tags:
- Data Visualization
- Robotic Controls
summary: An algorithm and visual encoding to explain unexpected multi-robot system behavior
featured_image: images/publications/a-visual-analytics-approach-to-debugging- cooperative-autonomous-multi-robot-systems-worldviews.png
alt_text: How the algorithm computes differences between robot worldviews
---
Autonomous multi-robot systems, where a team of robots shares information to perform tasks that are beyond an individual robot’s abilities, hold great promise for a number of applications, such as planetary exploration missions. Each robot in a multi-robot system that uses the shared-world coordination paradigm autonomously schedules which robot should perform a given task, and when, using its worldview–the robot’s internal representation of its belief about both its own state, and other robots’ states. A key problem for operators is that robots’ worldviews can fall out of sync (often due to weak communication links), leading to desynchronization of the robots’ scheduling decisions and inconsistent emergent behavior (e.g., tasks not performed, or performed by multiple robots). Operators face the time-consuming and difficult task of making sense of the robots’ scheduling decisions, detecting de-synchronizations, and pinpointing the cause by comparing every robot’s worldview. To address these challenges, we introduce MOSAIC Viewer, a visual analytics system that helps operators (i) make sense of the robots’ schedules and (ii) detect and conduct a root cause analysis of the robots’ desynchronized worldviews. Over a year-long partnership with roboticists at the NASA Jet Propulsion Laboratory, we conduct a formative study to identify the necessary system design requirements and a qualitative evaluation with 12 roboticists. We find that MOSAIC Viewer is faster- and easier-to-use than the users’ current approaches, and it allows them to stitch low-level details to formulate a high-level understanding of the robots’ schedules and detect and pinpoint the cause of the desynchronized worldviews.