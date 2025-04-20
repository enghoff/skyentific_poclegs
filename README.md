# Berkeley Humanoid Traning Code

[![IsaacSim](https://img.shields.io/badge/IsaacSim-4.5.0-silver.svg)](https://docs.omniverse.nvidia.com/isaacsim/latest/overview.html)
[![Isaac Lab](https://img.shields.io/badge/IsaacLab-2.0.0-silver)](https://isaac-sim.github.io/IsaacLab)
[![Python](https://img.shields.io/badge/python-3.13-blue.svg)](https://docs.python.org/3/whatsnew/3.13.html)
[![Linux platform](https://img.shields.io/badge/platform-linux--64-orange.svg)](https://releases.ubuntu.com/20.04/)

## Overview

This repository is a fork of the [isaac_berkeley_humanoid](https://github.com/HybridRobotics/isaac_berkeley_humanoid) repository and integrates code for the [Skyentific BipedalRobotSim](https://github.com/SkyentificGit/BipedalRobotSim) project featured on [Skyentific's Youtube channel](https://www.youtube.com/watch?v=xwOaStX0mxE)

The repository includes a policy model from an approximately 12-hour training run.

### Installation

- Install Isaac Sim and Isaac Lab, see
  the [IsaacSim & IsaacLab installation](https://isaac-sim.github.io/IsaacLab/main/source/setup/installation/index.html)

## Run

Training an agent with RSL-RL on Velocity-Rough-Skyentific-Poclegs-v0:

```
# run script for training
${ISAAC_LAB_PATH}/isaaclab.sh -p scripts/rsl_rl/train.py --task Velocity-Rough-Skyentific-Poclegs-v0
# run script for playing
${ISAAC_LAB_PATH}/isaaclab.sh -p scripts/rsl_rl/play.py --task Velocity-Rough-Skyentific-Poclegs-Play-v0
```

## Publications

If you use this work in an academic context, please consider citing the following publications:

    @misc{2407.21781,
    Author = {Qiayuan Liao and Bike Zhang and Xuanyu Huang and Xiaoyu Huang and Zhongyu Li and Koushil Sreenath},
    Title = {Berkeley Humanoid: A Research Platform for Learning-based Control},
    Year = {2024},
    Eprint = {arXiv:2407.21781},
    }
