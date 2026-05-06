---
layout: project
title: ODP 6 – Exhibit and Client Report
description: Final client-facing report and exhibit summary for the Save the Grapes system.
image: /assets/images/assemblymain.png
technologies: [CAD, Prototyping, Testing, Arduino]
permalink: /projects/odp6/
hidden_from_projects: true
back_url: /projects/odp/
back_label: Back to ODP
---

## ODP 6 – Client Report

### Context and Problem Statement

<p style="line-height: 1.6;">
  Spotted lanternflies (SLFs) are an invasive agricultural pest that threaten grape
  production by feeding on plant sugars, contaminating harvests, and contributing to
  sooty mold growth through honeydew excretion. Because direct removal from vines is
  impractical and post-harvest removal is risky, this project explores a different
  strategy: attracting SLFs away from grape vines entirely.
</p>

### Final Prototype and Application

<p style="line-height: 1.6;">
  The Save the Grapes system is designed as a decoy structure that lures SLFs away
  from vineyard vines. It uses a sugary attractant meant to mimic Tree of Heaven sap
  and then targets the insects with vinegar spraying through side-mounted sprayers.
  In operation, the device is meant to be placed in a vineyard, turned on, and run
  autonomously with minimal maintenance.
</p>

### How the System Works

<ol style="line-height: 1.6;">
  <li><strong>Sap Attraction:</strong> A sugar solution is pumped through the central pole to create an attractive feeding source.</li>
  <li><strong>Targeted Elimination:</strong> Once insects gather, vinegar is sprayed using servo-actuated sprayers.</li>
</ol>

### Key Features

<ol style="line-height: 1.6;">
  <li>Adjustable spray angles for coverage optimization</li>
  <li>Compact footprint for vineyard integration</li>
  <li>Arduino-controlled automation</li>
  <li>Low-toxicity vinegar-based treatment</li>
</ol>

### Assembly Summary

<p style="line-height: 1.6;">
  The box exterior is designed for rapid assembly and disassembly. The panels use a
  lip feature to maintain box geometry and are fastened with screws for rigidity.
  The lid is made of two loosely press-fit pieces to allow quick access to internal
  electronics and fluid reservoirs. Inside the box, an electrical board mounts the
  electronics, while jumper wires and Wago connectors simplify parallel connections.
  A 3D-printed rotational-to-linear linkage allows the servo motors to actuate the
  sprayer heads.
</p>

### Testing Details and Results

<h3 style="margin-top: 1.5rem;">1. Sap Drainage Test</h3>

<p style="line-height: 1.6;">
  To estimate how long the sap reservoir could last in the field, the team mixed
  200 g sucrose with 300 g water to approximate Tree of Heaven sap viscosity
  (~5 mPa·s), then pumped the solution for 10 minutes while recording level changes
  every 2.5 minutes.
</p>

<ul style="line-height: 1.6;">
  <li>Drainage rate: 0.5 mL/min</li>
  <li>Equivalent operating use: about 6 mL/day during working hours</li>
  <li>Implication: a 1000 mL reservoir would need refilling about every 167 days</li>
</ul>

<h3 style="margin-top: 1.5rem;">2. Spray Angle and Coverage</h3>

<p style="line-height: 1.6;">
  To determine the best sprayer angle, the central pole was covered in paper,
  sprayed at different angles, and evaluated based on damp area coverage.
</p>

<ul style="line-height: 1.6;">
  <li>Optimal working angle: 65 degrees</li>
  <li>Coverage achieved: 86%</li>
</ul>

<h3 style="margin-top: 1.5rem;">3. Battery Life</h3>

<p style="line-height: 1.6;">
  Power consumption calculations showed that VineGuard can operate for
  approximately 8.2 days on a single battery charge, and the modular battery design
  allows users to balance cost and serviceability depending on deployment needs.
</p>

### Conclusion and Recommendation

<p style="line-height: 1.6;">
  Based on the reported test results, VineGuard appears to be a feasible and
  effective low-toxicity solution for mitigating SLF damage in vineyards. The system
  delivered attractant at controlled flow rates, achieved strong spray coverage at
  the best tested angle, and showed promising autonomy and low maintenance
  requirements.
</p>

<p style="line-height: 1.6;">
  The recommended next step is field testing. The report specifically notes that
  future work should evaluate the best attractant, determine ideal placement for
  gathering insects, and modify the device aesthetics so it can be better
  camouflaged within a vineyard.
</p>

### PDF Appendix

<p style="line-height: 1.6;">
 
</p>
<p style="margin-top: 1.5rem;">
</p>