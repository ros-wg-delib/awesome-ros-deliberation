<!--lint disable awesome-git-repo-age-->
<!--TODO: remove after 10 June 2023-->

# Awesome Robotic Deliberation [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[![GitHub](https://img.shields.io/github/license/ros-wg-delib/awesome-ros-deliberation?style=flat-square)](LICENSE) [![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ros-wg-delib/awesome-ros-deliberation/awesome-lint.yml?style=flat-square)](https://github.com/ros-wg-delib/awesome-ros-deliberation/actions)
> A curated list of awesome tools, libraries and resources for deliberation in ROS 2.

Deliberation is the topmost layer in a robotics architecture sometimes also called mission or planning layer. It aims at controlling the robots behavior towards its extended goal or function. This includes pre-programmed state machines, automated symbolic planning as well as behavioral reaction to unforeseen situations happening at runtime.

## Contents

- [Packages](#packages)
- [Presentations](#presentations)
- [Papers](#papers)
- [Podcasts](#podcasts)
- [Demos](#demos)

## Packages

- [BehaviorTree.cpp](https://github.com/BehaviorTree/BehaviorTree.ROS) - Implementation of behavior trees in C++.
- [FlexBE](https://github.com/FlexBE/flexbe_behavior_engine) - State machine implementation with web-based GUI.
- [MERLIN2](https://github.com/MERLIN2-ARCH/merlin2) - PDDL Planner.
- [PlanSys2](https://github.com/PlanSys2/ros2_planning_system) - PDDL Planner.
- [SkiROS2](https://github.com/RVMI/skiros2) - Skill-based framework executing PDDL plans as behavior trees.
- [SMACC2](https://github.com/robosoft-ai/SMACC2) - State machine implementation in C++.
- [YASMIN](https://github.com/uleroboticsgroup/yasmin) - State machine implementation for C++ and Python.

## Presentations

- [BehaviorTree.CPP 4.0. What is new and roadmap](https://vimeo.com/767160437) - Davide Faconti, Picknik @ ROScon 2022 ([slides](http://download.ros.org/downloads/roscon/2022/BehaviorTree.CPP%204.0.%20What%20is%20new%20and%20roadmap.pdf)).
- [System Modes - model-based run-time state management of large systems](https://vimeo.com/767165876) - Ralph Lange, Bosch Research @ ROScon 2022 ([slides](http://download.ros.org/downloads/roscon/2022/System%20Modes%20-%20model-based%20run-time%20state%20management%20of%20large%20systems.pdf)).
- [SMACC2, an open-source, event-driven, asynchronous, behavioral state machine library for ROS2 applications written in C++](https://vimeo.com/649655394/f9b25be7f9) - Brett Aldrich, ROBOSOFT AI @ ROScon 2021.
- [PackML2: State Machine Based System Programming, Monitoring and Control in ROS2](https://vimeo.com/378683073) - Dejanira Araiza-Illan, ROS-Industrial Consortium Asia Pacific @ ROScon 2019 ([slides](https://roscon.ros.org/2019/talks/roscon2019_packml2.pdf)).
- [JdeRobot VisualStates: Visual tool for generating automata based robot behaviors](https://vimeo.com/293530044) - Okan Asik, JdeRobot @ ROScon 2018 Lightning Talks ([repo](https://github.com/JdeRobot/VisualStates)).

## Papers

- [Optimized Execution of PDDL Plans using Behavior Trees
](https://arxiv.org/abs/2101.01964?s=08) - Francisco Martín et. al.

## Podcasts

- [State Machines for Complex Robot Behavior](https://www.sensethinkact.com/episodes/10-brett-aldrich) - With Brett Aldrich, author of SMACC2.

## Demos

- [Simulation of Robot using Behavior Tree](https://www.youtube.com/watch?v=a0ve2CH245Y) - MOOD2BE, part of Robmosys.
