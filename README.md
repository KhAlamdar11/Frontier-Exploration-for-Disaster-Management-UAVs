# Frontier Exploration for Disaster Management UAVs

This ROS package provides a 2D frontier exploration stack for autonomous navigation of UAVs. It includes frontier extraction, candidate point generation, path planning and motion planning modules. The motion planning module is interfaced with Pixhawk (PX4) controller. The entire package is modular in nature and path planning or motion planning modules can be easily replaced as per need.

Please cite our paper if you use this project in your research:
- [__FUEL: Fast UAV Exploration using Incremental Frontier Structure and Hierarchical Planning__](https://arxiv.org/abs/2010.11561), Boyu Zhou, Yichen Zhang, Xinyi Chen, Shaojie Shen, IEEE Robotics and Automation Letters (**RA-L**) with ICRA 2021 option

```
@article{zhou2021fuel,
  title={FUEL: Fast UAV Exploration Using Incremental Frontier Structure and Hierarchical Planning},
  author={Zhou, Boyu and Zhang, Yichen and Chen, Xinyi and Shen, Shaojie},
  journal={IEEE Robotics and Automation Letters},
  volume={6},
  number={2},
  pages={779--786},
  year={2021},
  publisher={IEEE}
}
```
