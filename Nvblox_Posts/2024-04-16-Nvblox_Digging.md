---
layout: post
title:  "Nvblox Digging"
---

# Nvblox Digging
## Scripts
### Static Reconstruction 
Launch two files <br/>
start_isaac_sim.py & isaac_sim_example.launch.py <br/>
```
./python.sh ${ISAAC_ROS_WS}/src/isaac_ros_nvblox/nvblox_examples/nvblox_isaac_sim/omniverse_scripts/start_isaac_sim.py --gpu_physics_enabled
ros2 launch nvblox_examples_bringup isaac_sim_example.launch.py
```

**start_isaac_sim.py** <br/>
-File Path: https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_nvblox/blob/main/nvblox_examples/nvblox_isaac_sim/omniverse_scripts/start_isaac_sim.py <br/>
**isaac_sim_example.launch.py** <br/>
-File Path: https://github.com/NVIDIA-ISAAC-ROS/isaac_ros_nvblox/blob/main/nvblox_examples/nvblox_examples_bringup/launch/isaac_sim_example.launch.py <br/>

## Scene
**carter_warehouse_navigation.usd** <br/>
Link: http://omniverse-content-production.s3-us-west-2.amazonaws.com/Assets/Isaac/2023.1.1/Isaac/Samples/NvBlox/carter_warehouse_navigation.usd <br/>
A file located originally in Nucleus Server <br/>
![Nvblox_digging5](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/fe5fcd1f-a211-41d9-abc8-adf874310570) <br/>
-Overall Hierarchy <br/>
![Nvblox_digging6](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/75ef0f7e-063b-41d9-a0ee-d03177afe899) <br/>
-ActionGraph: <br/>
-Robot Structure: <br/>
(1)RPLidar <br/>
RPLIDAR S2E <br/>
![Nvblox_digging8](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/1e5d5956-739c-4921-b0d5-8baf7e705df8) <br/>
![Nvblox_digging9](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/01052153-5999-47a0-af99-422c143a59a4) <br/>
RPLIDAR S2E_01 <br/>
![Nvblox_digging10](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/050dbae3-1663-4335-9e53-5d167161ede2) <br/>



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


