# PX4-CBF

## Safety Filter Overview

This repository presents the instructions to use the embedded CBF-based safety filter for collision avoidance, designed for integration into the PX4 Autopilot.
It relies on online onboard range measurements and velocity estimation.
The safety filter is integrated into the PX4 position/velocity control loop and minimally modifies the acceleration setpoint to prevent collisions. 

## Dependencies

## Build / Install Instructions

## Build for Modalai voxl SDK

## Reference, Acknowledgments

If you use this work in your research, please cite the following publication:

```
@INPROCEEDINGS{Harms2025Safe,
  AUTHOR={Marvin Harms and Martin Jacquet and Kostas Alexis},
  TITLE={Safe Quadrotor Navigation using Composite Control Barrier Functions},
  BOOKTITLE={IEEE International Conference on Robotics and Automation (ICRA)},
  YEAR={2025},
  URL={https://arxiv.org/abs/2502.04101},
}
```

The embedded implementation work is currently under review.

We would like to acknowledge the participation of [Morten Nissov](https://github.com/mnissov) and [Nazar Misyats](https://github.com/Krafpy) to the proposed implementation.

## Contacts

* [Marvin Harms](mailto:marvin.c.harms@ntnu.no)
* [Morten Nissov](mailto:morten.nissov@ntnu.no)
* [Martin Jacquet](mailto:marvin.jacquet@ntnu.no)
* [Kostas Alexis](mailto:konstantinos.alexis@ntnu.no)
