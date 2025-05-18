# Awesome Robotic Platforms

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/ChuangYan2/awesome-robotic-platforms)](https://github.com/ChuangYan2/awesome-robotic-platforms/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ChuangYan2/awesome-robotic-platforms)](https://github.com/ChuangYan2/awesome-robotic-platforms/network/members)
[![GitHub issues](https://img.shields.io/github/issues/ChuangYan2/awesome-robotic-platforms)](https://github.com/ChuangYan2/awesome-robotic-platforms/issues)
[![GitHub license](https://img.shields.io/github/license/ChuangYan2/awesome-robotic-platforms)](https://github.com/ChuangYan2/awesome-robotic-platforms/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/ChuangYan2/awesome-robotic-platforms/pulls)

> A curated list of awesome robotic platforms for research, education, and industry applications

## Contents

- [Awesome Robotic Platforms](#awesome-robotic-platforms)
  - [Contents](#contents)
  - [Introduction](#introduction)
  - [How to Contribute](#how-to-contribute)
  - [Platforms](#platforms)
    - [Humanoid Robots](#humanoid-robots)
    - [Bipedal Robots](#bipedal-robots)
    - [Quadrupedal Robots](#quadrupedal-robots)
    - [Mobile Platforms](#mobile-platforms)
    - [Manipulators](#manipulators)
    - [Drones \& Aerial Platforms](#drones--aerial-platforms)

## Introduction

This repository aims to be a comprehensive collection of robotics platforms across various form factors and applications. The goal is to provide a central reference for researchers, educators, students, and industry professionals to discover and compare robotic platforms for different use cases.

## How to Contribute

Contributions are highly encouraged! If you know of a robotic platform that is not listed here, please submit a pull request. Please follow these guidelines:

1. Make sure the platform is notable and relevant to robotics
2. Follow the format used for existing entries
3. Place the entry in the appropriate category
4. If needed, suggest new categories
5. Provide as much detailed information as possible

For more details, see [CONTRIBUTING.md](CONTRIBUTING.md).

## Platforms

### Humanoid Robots

| Name | Developer | Key Features | Height | DOF | Payload | Power | Software | Year | Link | Open Source | Price Range |
|------|-----------|--------------|--------|-----|---------|-------|----------|------|------|-------------|-------------|
| Atlas | Boston Dynamics | Dynamic balancing, parkour capabilities, whole-body control | 1.5m | 28 | 11kg | Electric | Proprietary | 2013 (Latest gen: 2023) | [Link](https://www.bostondynamics.com/atlas) | No | N/A (Research) |
| Digit | Agility Robotics | Bipedal delivery robot, stair climbing, compact design | 1.57m | 20 | 16kg | Electric (3hr) | ROS compatible | 2020 | [Link](https://agilityrobotics.com/robots#digit) | No | $250k-$500k |
| NAO | SoftBank Robotics | Compact, programmable, human-robot interaction focus | 58cm | 25 | 0.3kg | Electric (90min) | NAOqi, ROS | 2008 | [Link](https://www.softbankrobotics.com/emea/en/nao) | No | $10k-$15k |
| Pepper | SoftBank Robotics | Social interaction, omnidirectional wheel base, tablet interface | 1.2m | 20 | Light items | Electric (12hr) | NAOqi, ROS | 2014 | [Link](https://www.softbankrobotics.com/emea/en/pepper) | No | $20k-$30k |

### Bipedal Robots

| Name | Developer | Key Features | Height | DOF | Payload | Power | Software | Year | Link | Open Source | Price Range |
|------|-----------|--------------|--------|-----|---------|-------|----------|------|------|-------------|-------------|
| Cassie | Agility Robotics | Dynamic running, efficient walking, robust design | 0.9m | 10 | - | Electric (1hr+) | ROS compatible | 2017 | [Link](https://agilityrobotics.com/robots#cassie) | No | ~$250k |
| AMBER | AMBER Lab | Research platform for prosthetics and locomotion studies | 0.6m | 6-12 | - | Electric | ROS | 2008 | [Link](https://www.bipedalrobotics.com/) | Partial | Research |
| Bolt | Oregon State | High-speed running, compliant actuation | 0.7m | 12 | - | Electric | Custom | 2022 | [Link](https://mime.engineering.oregonstate.edu/research/drl/robots/bolt) | Partial | Research |

### Quadrupedal Robots

| Name | Developer | Key Features | Size | DOF | Payload | Power | Software | Year | Link | Open Source | Price Range |
|------|-----------|--------------|--------|-----|---------|-------|----------|------|------|-------------|-------------|
| Spot | Boston Dynamics | Dynamic mobility, stairs, rough terrain, modular payload system | 0.7m | 12 | 14kg | Electric (90min) | API, Python SDK | 2019 | [Link](https://www.bostondynamics.com/spot) | No | $75k+ |
| ANYmal | ANYbotics | Industrial inspection, rough terrain, sensor suite | 0.5m | 12 | 10kg | Electric (3hr) | ROS | 2016 | [Link](https://www.anybotics.com/anymal/) | No | $150k+ |
| MIT Mini Cheetah | MIT | High-speed locomotion, flips, modular design | 0.3m | 12 | Small | Electric | ROS | 2019 | [Link](https://biomimetics.mit.edu/research/mini-cheetah-robot) | Yes | DIY |
| Unitree Go1 | Unitree Robotics | Consumer-focused, following capabilities | 0.4m | 12 | 5kg | Electric (1.5hr) | ROS, API | 2021 | [Link](https://www.unitree.com/go1/) | No | $2.7k-$20k |

### Mobile Platforms

| Name | Developer | Key Features | Size | Payload | Speed | Power | Software | Year | Link | Open Source | Price Range |
|------|-----------|--------------|------|---------|-------|-------|----------|------|------|-------------|-------------|
| TurtleBot4 | Clearpath Robotics | Educational, ROS 2 native, built on iRobot Create 3 | Small | 9kg | 0.5m/s | Electric (2.5hr) | ROS 2 | 2022 | [Link](https://clearpathrobotics.com/turtlebot-4/) | Yes | $1.6k-$3k |
| Clearpath Jackal | Clearpath Robotics | Outdoor all-terrain UGV | Med | 20kg | 2m/s | Electric (4hr) | ROS | 2014 | [Link](https://clearpathrobotics.com/jackal-small-unmanned-ground-vehicle/) | No | $12k+ |
| Clearpath Husky | Clearpath Robotics | Rugged outdoor platform | Large | 75kg | 1m/s | Electric (3hr) | ROS | 2012 | [Link](https://clearpathrobotics.com/husky-unmanned-ground-vehicle-robot/) | No | $20k+ |
| MiR250 | Mobile Industrial Robots | Autonomous industrial material transport | Med | 250kg | 2m/s | Electric (13hr) | Proprietary, REST API | 2020 | [Link](https://www.mobile-industrial-robots.com/solutions/robots/mir250/) | No | $30k+ |

### Manipulators

| Name | Developer | Key Features | Reach | Payload | DOF | Power | Software | Year | Link | Open Source | Price Range |
|------|-----------|--------------|-------|---------|-----|-------|----------|------|------|-------------|-------------|
| UR5e | Universal Robots | Collaborative, easy programming | 850mm | 5kg | 6 | Electric | PolyScope, ROS | 2018 | [Link](https://www.universal-robots.com/products/ur5-robot/) | No | $35k+ |
| Kinova Gen3 | Kinova Robotics | Lightweight, adaptive | 902mm | 2kg | 7 | Electric | Kinova API, ROS | 2019 | [Link](https://www.kinovarobotics.com/product/gen3-robots) | No | $35k+ |
| Franka Emika Panda | Franka Emika | Research-grade collaborative robot | 855mm | 3kg | 7 | Electric | Franka Control Interface, ROS | 2017 | [Link](https://www.franka.de/) | No | $17k+ |
| Stretch RE1 | Hello Robot | Mobile manipulation, household assistance | 1.37m | 1.5kg | 4+ | Electric (8hr) | ROS | 2020 | [Link](https://hello-robot.com/product) | No | $17.5k |

### Drones & Aerial Platforms

| Name | Developer | Key Features | Size | Payload | Flight Time | Software | Year | Link | Open Source | Price Range |
|------|-----------|--------------|------|---------|-------------|----------|------|------|-------------|-------------|
| DJI Matrice 300 RTK | DJI | Professional aerial inspections | Large | 2.7kg | 55min | DJI SDK | 2020 | [Link](https://www.dji.com/matrice-300) | No | $13k+ |
| Intel Aero | Intel | Developer-focused drone platform | Small | 0.5kg | 20min | PX4, ROS | 2016 | [Link](https://www.intel.com/content/www/us/en/products/drones/aero-ready-to-fly.html) | Partial | $1.5k |
| Crazyflie 2.1 | Bitcraze | Micro quadcopter, research and education | Tiny | 15g | 7min | Custom, ROS | 2016 | [Link](https://www.bitcraze.io/products/crazyflie-2-1/) | Yes | $180 |