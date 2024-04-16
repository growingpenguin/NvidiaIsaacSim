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
-Robot Structure: <br/>
(1)RPLidar <br/>
RPLIDAR S2E <br/>
![Nvblox_digging8](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/1e5d5956-739c-4921-b0d5-8baf7e705df8) <br/>
![Nvblox_digging20](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/09c152bb-893c-4bc3-90fa-8f431e3eee65) <br/>
RPLIDAR S2E_01 <br/>
![Nvblox_digging10](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/050dbae3-1663-4335-9e53-5d167161ede2) <br/>
![Nvblox_digging21](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/0b158b01-dce7-4803-9f25-aac952f9f1b4) <br/>
front_RPLidar <br/>
![Nvblox_digging25](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/d8a7659e-8cac-4433-9c27-a1bfbe931982) <br/>
rear_RPLidar <br/>
![Nvblox_digging26](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/f6eb1466-72a1-41c2-b172-36ff2c4acd13) <br/>


(2)XT-32 <br/>
=> Load Failure <br/>
![Nvblox_digging22](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/6fbf0e15-3d29-46d2-825c-59a29560518c) <br/>
![Nvblox_digging23](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/b58d54e4-aa62-4580-ab30-ef31d66251eb) <br/>
(3)Hawk Stereo Camera <br/>
front_hawk <br/>
![Nvblox_digging11](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/d3493244-ea13-462d-8175-ca0939ad74d4) <br/>
![Nvblox_digging15](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/a3ea13c2-9018-401f-b574-85dce136aa09) <br/>
left_hawk <br/>
![Nvblox_digging12](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/086cb12d-90ac-42ff-b831-563351ef3e5e) <br/>
![Nvblox_digging16](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/2dbc1048-63e0-41f6-8c52-b63b85cb6f1e) <br/>
right_hawk <br/>
![Nvblox_digging13](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/f7835e2d-88a6-4ada-bd22-26c345d9e254) <br/>
![Nvblox_digging17](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/1017ec2b-6692-4db0-a9f9-187fd258aad6) <br/>
back_hawk <br/>
![Nvblox_digging24](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/879ee772-ffe2-4214-866a-746099686321) <br/>
![Nvblox_digging18](https://github.com/growingpenguin/growingpenguin.github.io/assets/110277903/1eb29f86-98dd-414f-b015-d56214392e21) <br/>


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


