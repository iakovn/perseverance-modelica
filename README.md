Perseverance
=====

This is a model of the Perseverance rover.

![driving over a cleat](Perseverance/Resources/images/cleat.gif)

Prerequisites
-------
The model package is based on **Vehicle Dynamics Library** and **Electrification Library** from Modelon. All prerequisites are included in an installation of **Modelon Impact Pro**.

If you have access to the cloud installation @https://jhmi.modelon.com you can use workspace link: [Modelon Impact: Perseverance](https://jhmi.modelon.com/hub/user-redirect/impact/customizations/workspace_management/index.html?share=eyJkZWZpbml0aW9uIjp7Im5hbWUiOiJQZXJzZXZlcmFuY2UyIiwiZm9ybWF0IjoiMS4wLjAiLCJndWlkIjoiM2Y3ZmU4MGE1ZjU5NGNiZWFiY2UyNTg0ZDBjMWVmMzUiLCJkZXNjcmlwdGlvbiI6IiIsImNyZWF0ZWRCeSI6ImI2N2RmZmExLWM5MjAtNDUyOC1hN2Y2LTgyNGRkZDgzYjM0YiIsImNyZWF0ZWRBdCI6MTY2NDg2Njk4OTAzMywiZGVmYXVsdFByb2plY3RJZCI6IjI1NTE3MTYzYWNjZjUzYzQ0NTVkYjU3MzVjYTRlOTY0ZTM2NWJhYWMiLCJwcm9qZWN0cyI6W3sicmVmZXJlbmNlIjp7ImlkIjoiMjU1MTcxNjNhY2NmNTNjNDQ1NWRiNTczNWNhNGU5NjRlMzY1YmFhYyIsInZjc1VyaSI6ImdpdCtodHRwczovL2dpdGh1Yi5jb20vaWFrb3ZuL3BlcnNldmVyYW5jZS1tb2RlbGljYUBpbXBhY3QtcHJvamVjdCJ9LCJkaXNhYmxlZCI6ZmFsc2UsImRpc2FibGVkQ29udGVudCI6W119XSwiZGVwZW5kZW5jaWVzIjpbeyJyZWZlcmVuY2UiOnsiaWQiOiI5OGJjMTRhNjJlY2QyZTRhMzhkOWFjOTIzYWFmN2U5YWMzZjllNjM1IiwibmFtZSI6Ik1vZGVsaWNhIiwidmVyc2lvbiI6IjMuMi4zIn0sImRpc2FibGVkIjpmYWxzZSwiZGlzYWJsZWRDb250ZW50IjpbXX0seyJyZWZlcmVuY2UiOnsiaWQiOiI4M2U2ZTU5MTdmYWIxMzgxYWQ3OTMxY2RhY2JlM2UyM2QyMzY4Y2Y0IiwibmFtZSI6Ik1vZGVsaWNhIiwidmVyc2lvbiI6IjQuMC4wIn0sImRpc2FibGVkIjp0cnVlLCJkaXNhYmxlZENvbnRlbnQiOltdfSx7InJlZmVyZW5jZSI6eyJpZCI6IjA4YzYwNWE3NGQ1MzYxOTg1MDdlODlmN2Y2MjA0NTRmNzZmZjkxODciLCJuYW1lIjoiTW9kZWxvbiIsInZlcnNpb24iOiIzLjcuMCJ9LCJkaXNhYmxlZCI6ZmFsc2UsImRpc2FibGVkQ29udGVudCI6W119LHsicmVmZXJlbmNlIjp7ImlkIjoiZjNjNDFhM2M4ZTU5MDkwMDgwYWQ1Nzg2OGIyODJhNjI3OWFjNDA4YyIsIm5hbWUiOiJWZWhpY2xlRHluYW1pY3MiLCJ2ZXJzaW9uIjoiMy43LjAifSwiZGlzYWJsZWQiOmZhbHNlLCJkaXNhYmxlZENvbnRlbnQiOltdfSx7InJlZmVyZW5jZSI6eyJpZCI6IjFkODdkMmYzOWEzOWNkZjJhZjRjZTM5MzEwYzMzZWM5MTI1YzM1ZjQiLCJuYW1lIjoiRWxlY3RyaWZpY2F0aW9uIiwidmVyc2lvbiI6IjEuNi4wIn0sImRpc2FibGVkIjpmYWxzZSwiZGlzYWJsZWRDb250ZW50IjpbXX1dfX0=)

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