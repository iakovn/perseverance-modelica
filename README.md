Perseverance
=====

This is a model of the Perseverance rover.

![driving over a cleat](Perseverance/Resources/images/cleat.gif)

Prerequisites
-------
The model package is based on **Vehicle Dynamics Library** and **Electrification Library** from Modelon. All prerequisites are included in an installation of **Modelon Impact Pro**.

If you have access to the cloud installation @https://jhmi.modelon.com you can use workspace link: [Modelon Impact: Perseverance](https://jhmi.modelon.com/hub/user-redirect/impact/customizations/workspace_management/index.html?share=eyJkZWZpbml0aW9uIjp7Im5hbWUiOiJQZXJzZXZlcmFuY2UiLCJmb3JtYXQiOiIxLjAiLCJkZXNjcmlwdGlvbiI6IiIsImNyZWF0ZWRCeSI6ImI2N2RmZmExLWM5MjAtNDUyOC1hN2Y2LTgyNGRkZDgzYjM0YiIsImNyZWF0ZWRBdCI6MTY2MDkxMzcwNTI0MSwiZGVmYXVsdFByb2plY3RJZCI6IjM2ZTQ1NzhiZmExYTgzODJiZDliYTczMTNhNjk0OThiZTczMTc1YWEiLCJwcm9qZWN0cyI6W3sicmVmZXJlbmNlIjp7ImlkIjoiNjI5YzlkZDA1MmQ4ZjZlMjVlNGUwYjI0MTAzOWM4NTlhNGVlOTY3YiIsInZjc1VyaSI6ImdpdCtodHRwczovL2dpdGh1Yi5jb20vaWFrb3ZuL3BlcnNldmVyYW5jZS1tb2RlbGljYS5naXRAaW1wYWN0LXByb2plY3QifSwiZGlzYWJsZWQiOmZhbHNlLCJkaXNhYmxlZENvbnRlbnQiOltdfV0sImRlcGVuZGVuY2llcyI6W3sicmVmZXJlbmNlIjp7ImlkIjoiODRmYjFjMzdhYmU2ZWQ5N2E1Mzk3MmZiNzIzOTYzMGUxMjEyNDM4YiIsIm5hbWUiOiJNU0wiLCJ2ZXJzaW9uIjoiMy4yLjMifSwiZGlzYWJsZWQiOmZhbHNlLCJkaXNhYmxlZENvbnRlbnQiOltdfSx7InJlZmVyZW5jZSI6eyJpZCI6ImNkYmRlODkyMmJkMmM0OGMzOTJiMWI0YmI3NDBhZGMwMjczYzczN2MiLCJuYW1lIjoiTVNMIiwidmVyc2lvbiI6IjQuMC4wIn0sImRpc2FibGVkIjp0cnVlLCJkaXNhYmxlZENvbnRlbnQiOltdfSx7InJlZmVyZW5jZSI6eyJpZCI6IjE1YzViMDdlZjg3NTY4MDJlY2U5ZjJiNzI0YzJhYWNkZGVkNzJiOTEiLCJuYW1lIjoiTW9kZWxvbiIsInZlcnNpb24iOiIzLjcuMCJ9LCJkaXNhYmxlZCI6ZmFsc2UsImRpc2FibGVkQ29udGVudCI6W119LHsicmVmZXJlbmNlIjp7ImlkIjoiYzBiYTQxYjQ4MGMwMjdlNzQzMTgyYzY3MTU5ZDcwN2QzZGJjOTY4NCIsIm5hbWUiOiJWZWhpY2xlRHluYW1pY3MiLCJ2ZXJzaW9uIjoiMy43LjAifSwiZGlzYWJsZWQiOmZhbHNlLCJkaXNhYmxlZENvbnRlbnQiOltdfSx7InJlZmVyZW5jZSI6eyJpZCI6IjM1ZmExNWI5M2E3NzYzYzJkNDA5NmJjMDBkMzkyYmNkNjM2OWZkYzMiLCJuYW1lIjoiRWxlY3RyaWZpY2F0aW9uIiwidmVyc2lvbiI6IjEuNi4wIn0sImRpc2FibGVkIjpmYWxzZSwiZGlzYWJsZWRDb250ZW50IjpbXX1dfX0=)

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