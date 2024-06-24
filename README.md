Perseverance
=====

This is a model of the Perseverance rover.

![driving over a cleat](Perseverance/Resources/images/cleat.gif)

Prerequisites
-------
The model package is based on **Vehicle Dynamics Library** and **Electrification Library** from Modelon. All prerequisites are included in an installation of **Modelon Impact Pro**.

If you have access to the cloud installation @https://jhmi.modelon.com you can use workspace link: [Modelon Impact: Perseverance](https://jhmi.modelon.com/hub/user-redirect/impact/customizations/workspace_management/index.html?share=eyJkZWZpbml0aW9uIjp7Im5hbWUiOiJQZXJzZXZlcmFuY2UiLCJkZXNjcmlwdGlvbiI6IiIsImRlZmF1bHRQcm9qZWN0SWQiOiIyNTUxNzE2M2FjY2Y1M2M0NDU1ZGI1NzM1Y2E0ZTk2NGUzNjViYWFjIiwicHJvamVjdHMiOlt7InJlZmVyZW5jZSI6eyJpZCI6IjI1NTE3MTYzYWNjZjUzYzQ0NTVkYjU3MzVjYTRlOTY0ZTM2NWJhYWMiLCJ2Y3NVcmkiOiJnaXQraHR0cHM6Ly9naXRodWIuY29tL2lha292bi9wZXJzZXZlcmFuY2UtbW9kZWxpY2FAaW1wYWN0LXByb2plY3QifSwiZGlzYWJsZWQiOmZhbHNlLCJkaXNhYmxlZENvbnRlbnQiOltdfV0sImRlcGVuZGVuY2llcyI6W3sicmVmZXJlbmNlIjp7ImlkIjoiZmVjNDNmNzc5MjU5NDliZDdlN2MwZjEwYWM0OWViYzExODlkYzg0MCIsIm5hbWUiOiJNb2RlbGljYSIsInZlcnNpb24iOiIzLjIuMyJ9LCJkaXNhYmxlZCI6ZmFsc2UsImRpc2FibGVkQ29udGVudCI6W119LHsicmVmZXJlbmNlIjp7ImlkIjoiYWMwNGE1ZGE5N2JjMmUxMWJmZmI3ZjQxYjI0ODVkYTM0Nzg0NmRmNiIsIm5hbWUiOiJNb2RlbGljYSIsInZlcnNpb24iOiI0LjAuMCJ9LCJkaXNhYmxlZCI6dHJ1ZSwiZGlzYWJsZWRDb250ZW50IjpbXX0seyJyZWZlcmVuY2UiOnsiaWQiOiI2NGI1MWE0MDY2OTY3YWUwNDFiZThmMzZjNGI0MDdhNTkwYzg2NmEzIiwibmFtZSI6Ik1vZGVsb24iLCJ2ZXJzaW9uIjoiMy43LjAifSwiZGlzYWJsZWQiOmZhbHNlLCJkaXNhYmxlZENvbnRlbnQiOltdfSx7InJlZmVyZW5jZSI6eyJpZCI6ImNhNGUwM2JkZjBiYzZjZjMxYTZlNGUxNGI2Njk1OTkxNzRhYTk1OGIiLCJuYW1lIjoiVmVoaWNsZUR5bmFtaWNzIiwidmVyc2lvbiI6IjMuNy4wIn0sImRpc2FibGVkIjpmYWxzZSwiZGlzYWJsZWRDb250ZW50IjpbXX0seyJyZWZlcmVuY2UiOnsiaWQiOiI2NGQ0M2UyMjRmZGFkYTBlZDhiMDA1YWQ4NzRhNDNkMTFmZjkzNzIyIiwibmFtZSI6IkVsZWN0cmlmaWNhdGlvbiIsInZlcnNpb24iOiIxLjYuMCJ9LCJkaXNhYmxlZCI6ZmFsc2UsImRpc2FibGVkQ29udGVudCI6W119XSwiZm9ybWF0IjoiMS4wLjAiLCJndWlkIjoiM2Y3ZmU4MGE1ZjU5NGNiZWFiY2UyNTg0ZDBjMWVmMzUiLCJjcmVhdGVkQnkiOiJiNjdkZmZhMS1jOTIwLTQ1MjgtYTdmNi04MjRkZGQ4M2IzNGIiLCJjcmVhdGVkQXQiOjE2NjQ4NjY5ODkwMzN9fQ==)

 The models can also be used in Dymola with separate installations of the required libraries, though the visualizers (glb files) are not supported.

Quick start
--------

In Perseverance.Experiments there are four example experiments that can be simulated out of the box:
 - **FlatPad** - Standing still on flat ground
 - **DrivingFlat** - Driving forward on flat ground at a constant speed
 - **DrivingCleats** - Driving over a rectangular cleat at a constant speed
 - **Spin** - Spin in place by driving wheels on each side in opposite directions and adding the appropriate steering angles to the corner wheels

Acknowledgements
-----------
The visualization elements are extracted from https://github.com/nasa/NASA-3D-Resources/tree/master/3D%20Models/perseverance-GLB. This is also where the main geometrical parameters are gathered.

Ingenuity
=====

This is a model of the Ingenuity helicopter.

![Hover](Ingenuity/Resources/images/hover.gif)

Prerequisites
-------
The model package is based on **Vehicle Dynamics Library** and **Electrification Library** from Modelon. All prerequisites are included in an installation of **Modelon Impact Pro**. The models can also be used in Dymola with separate installations of the required libraries, though the visualizers (glb files) are not supported.

Quick start
--------

In Ingenuity.Experiments there are six example experiments that can be simulated out of the box:
 - **ConstantThrust** - Constant thrust achieved by using Linear thrust force model
 - **Yaw** - Yaw motion achieved using a torque differential between the two rotors
 - **Hover** - Hovering motion at a constant altitude using AltitudeVelocityAnglesController and LinearPitchRoll thrust force model
 - **HoverRollPitch** - Roll and pitch motion at a constant altitude using AltitudeVelocityAnglesController and LinearPitchRoll thrust force model
 - **HoverVelocity** - Lateral and longitudinal velocity inputs at a constant altitude using AltitudeVelocityAnglesController and LinearPitchRoll thrust force model
 - **HoverPosition** - Lateral, longitudinal positon, altitude controller using AltitudePositionAnglesController and LinearPitchRoll thrust force model

Acknowledgements
-----------
The visualization elements are extracted from https://mars.nasa.gov/resources/25043/mars-ingenuity-helicopter-3d-model/. This is also where the main geometrical parameters are gathered.

ExampleModels
=====

This package contains experiments showing how both the Perseverance and Ingenuity models can be simulated together.

![Hover](ExampleModels/Resources/images/roverAndHelicopter.gif)
