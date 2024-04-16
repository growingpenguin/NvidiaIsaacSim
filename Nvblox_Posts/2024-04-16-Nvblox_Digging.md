---
layout: post
title:  "Nvblox Digging"
---

# Nvblox Digging
## Scripts
### Static Reconstruction 
Launch two files <br/>
start_isaac_sim.py & isaac_sim_example.launch.py <br/>

./python.sh ${ISAAC_ROS_WS}/src/isaac_ros_nvblox/nvblox_examples/nvblox_isaac_sim/omniverse_scripts/start_isaac_sim.py --gpu_physics_enabled
ros2 launch nvblox_examples_bringup isaac_sim_example.launch.py

## Scene
carter_warehouse_navigation.usd <br/>
Link: http://omniverse-content-production.s3-us-west-2.amazonaws.com/Assets/Isaac/2023.1.1/Isaac/Samples/NvBlox/carter_warehouse_navigation.usd <br/>
A file located originally in Nucleus Server <br/>


## Robot
**nova_carter.usd** <br/> 
![Nvblox_digging1](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/e1f09d00-7f37-4193-95de-77da7201b55c) <br/>
![Nvblox_digging4](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/83f7c758-02ee-4bb0-bfd9-67357c266698) <br/>
-Hierarchy <br/>
![Nvblox_digging2](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/3e6a7e37-1216-4b4c-9b7e-3da63a74a99c) <br/>
-Documentation: <br/>
https://docs.omniverse.nvidia.com/isaacsim/latest/landing_pages/carter_nova_landing_page.html <br/>
-Download robot as usd: <br/> 
http://omniverse-content-production.s3-us-west-2.amazonaws.com/Assets/Isaac/2023.1.1/Isaac/Robots/Carter/nova_carter.usd <br/>


