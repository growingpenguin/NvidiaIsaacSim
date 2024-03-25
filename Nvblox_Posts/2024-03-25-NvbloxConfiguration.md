---
layout: post
title:  "Nvblox Configuration"
---

# Nvblox Configuration
## Robot


## Camera
**Translate** <br/>
X-axis: Moving the object left or right <br/>
Y-axis: Moving the object up or down <br/>
Z-axis: Moving the object forward or backward <br/>
**Orient** <br/>
X-axis (Pitch): Tilting the object up or down <br/>
Y-axis (Yaw): Swiveling the object left or right <br/>
Z-axis (Roll): Rotating the object clockwise or counterclockwise <br/>
**Scale** <br/>
X-axis: Changes the object's width. Increasing the scale value stretches the object wider, while decreasing it makes the object narrower <br/>
Y-axis: Alters the object's height. A higher scale value increases the height, and a lower value decreases it <br/>
Z-axis: Affects the object's depth. Manipulating this value stretches or shrinks the object's size forward and backward <br/>


### Static Reconstruction Camera
![NvbloxConfiguration1](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/68a8719c-e944-4d80-bb46-ed50bf9ee09e) <br/>
12 Cameras in total <br/>
Camera Names: <br/>
**front_hawk** <br/>
front_hawk/camera_right, front_hawk/camera_left <br/>
camera_right <br/>
![NvbloxConfiguration2](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/24de445b-fc76-478d-8584-0ae13dce798d) <br/>
camera_left <br/>
![NvbloxConfiguration3](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/311dc232-db50-4b21-895b-08592b1e5270) <br/>
**left_hawk** <br/>
left_hawk/right/camera_right, left_hawk/left/camera_left <br/>
camera_right <br/>
![NvbloxConfiguration4](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/473a97f2-2de2-4eb3-85e0-749132dd1118) <br/>
camera_left <br/>
![NvbloxConfiguration5](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/b212110e-73c0-4013-ac68-4871d073ac00) <br/>
**right_hawk** <br/>
right_hawk/right/camera_right, right_hawk/left/camera_left <br/>
camera_right <br/>
![NvbloxConfiguration6](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/30d751af-b02c-413a-a570-9cc7c1272409) <br/>
camera_left <br/>
![NvbloxConfiguration7](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/ed6567d7-5df8-47d9-879c-e31a1522db31) <br/>
**back_hawk** <br/>
back_hawk/right/camera_right, back_hawk/left/camera_left <br/>
camera_right <br/>
![NvbloxConfiguration8](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/f2f30d61-67d9-473d-bb0a-4fe5582f8651) <br/>
camera_left <br/>
![NvbloxConfiguration9](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/baf70e73-f8b3-4e69-96ed-3b207ac75500) <br/>

**front_owl** <br/>
front_owl/camera <br/>
![NvbloxConfiguration10](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/76bd0a82-9487-4216-999f-5ede5bc08643) <br/>

**left_owl** <br/>
left_owl/camera <br/>
![NvbloxConfiguration11](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/471a12ae-44a6-47a6-99fe-90d0780b50f9) <br/>

**right_owl** <br/>
right_owl/camera <br/>
![NvbloxConfiguration12](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/6746a629-e39c-40f3-bebe-c20515224b04) <br/>

**back_owl** <br/>
back_owl/camera <br/>
![NvbloxConfiguration13](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/2d82c4ec-eb0e-450c-b551-2bc79fbabc96) <br/>

=> Summary <br/>
**hawk**
|   | x | y | z |
|---|----------|----------|----------|
| **Translate** | 0.0   | 0.0   | 0.0   | 
| **Orient** | 90.0   | -90.0   | 0.0   | 
| **Scale** | 1.0   | 1.0  | 1.0  | 




 
**owl** <br/>
|   | x | y | z |
|---|----------|----------|----------|
| **Translate** | 0.0   | 0.0   | 0.0   | 
| **Orient** | 0.0   | 0.0   | 0.0   | 
| **Scale** | 0.0   | 0.0  | 0.0  | 




Reference: <br/>
https://nvidia-isaac-ros.github.io/concepts/scene_reconstruction/nvblox/tutorials/tutorial_isaac_sim.html <br/>
https://docs.omniverse.nvidia.com/isaacsim/latest/gui_tutorials/tutorial_gui_camera_sensors.html <br/>
https://docs.omniverse.nvidia.com/isaacsim/latest/introductory_tutorials/tutorial_intro_interface.html#isaac-sim-app-tutorial-intro-interface <br/>
