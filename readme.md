<!--lint disable awesome-git-repo-age-->
<!--TODO: remove after 10 June 2023-->

# Awesome Robotic Deliberation [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

[![GitHub](https://img.shields.io/github/license/ros-wg-delib/awesome-ros-deliberation?style=flat-square)](LICENSE) [![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/ros-wg-delib/awesome-ros-deliberation/lint.yml?style=flat-square)](https://github.com/ros-wg-delib/awesome-ros-deliberation/actions)
> A curated list of awesome tools, libraries and resources for deliberation in ROS 2.

Deliberation is the topmost layer in a robotics architecture sometimes also called mission or planning layer.
It aims at controlling the robots behavior towards its extended goal or function.
This includes pre-programmed state machines, automated symbolic planning as well as behavioral reaction to unforeseen situations happening at runtime.

## Contents

- [Software Packages](#software-packages)
- [Presentations](#presentations)
- [Papers and Book Chapters](#papers-and-book-chapters)
- [Blog Posts](#blog-posts)
- [Podcasts](#podcasts)
- [Demos](#demos)

## Software Packages

### Task Planning and Execution Frameworks
- [CoSTAR Stack](http://cpaxton.github.io/costar_stack/) - A collaborative system for task automation and recognition.
- [MERLIN2](https://github.com/MERLIN2-ARCH/merlin2) - PDDL planning and execution framework, using Python and state machines.
- [MoveIt Task Constructor](https://github.com/ros-planning/moveit_task_constructor) - MoveIt add-on package that performs skeleton-based task and motion planning.
- [PlanSys2](https://github.com/PlanSys2/ros2_planning_system) - PDDL planning and execution framework, using C++ and behavior trees.
- [SkiROS2](https://github.com/RVMI/skiros2) - Skill-based platform with behavior trees, PDDL task-planning and knowledge integration.
- [UP4ROS2](https://github.com/aiplan4eu/UP4ROS2) - ROS 2 wrapper for the [AIPlan4EU Unified Planning library](https://github.com/aiplan4eu/unified-planning).

### Behavior Abstractions
- [BehaviorTree.CPP](https://github.com/BehaviorTree/BehaviorTree.ROS) - Implementation of behavior trees in C++.
- [FlexBE](https://github.com/FlexBE/flexbe_behavior_engine) - State machine implementation with web-based GUI
- [PyTrees ROS](https://github.com/splintered-reality/py_trees_ros) - ROS 2 wrapper for the [PyTrees](https://github.com/splintered-reality/py_trees) behavior tree library.
- [SMACC2](https://github.com/robosoft-ai/SMACC2) - State machine implementation in C++.
- [YASMIN](https://github.com/uleroboticsgroup/yasmin) - State machine implementation for C++ and Python.

### Application-Specific Packages
- [MoveIt Pro](https://picknik.ai/pro/) - ROS 2 based commercial software that uses BehaviorTree.CPP and MoveIt.
- [NEXUS](https://github.com/osrf/nexus) - A ROS 2 framework for orchestrating industrial robotic lines and cells.
- [pyrobosim](https://github.com/sea-bass/pyrobosim) - ROS 2 enabled 2D mobile robot simulator for behavior prototyping.
- [rmf_task](https://github.com/open-rmf/rmf_task) - Composable task definitions and multi-robot task allocation (MRTA) planner in C++.

## Presentations

- [BehaviorTree.CPP 4.0. What is new and roadmap](https://vimeo.com/767160437) - Davide Faconti, Picknik @ ROScon 2022 ([slides](http://download.ros.org/downloads/roscon/2022/BehaviorTree.CPP%204.0.%20What%20is%20new%20and%20roadmap.pdf)).
- [Behavior Trees for Home Service Robotics Tasks](https://www.youtube.com/watch?v=xbvMnpwXNPk) - Sebastian Castro, PickNik Robotics @ Behavior Trees in Robotics Seminar.
- [How custom tasks are defined, assigned, and executed in Open-RMF](https://vimeo.com/showcase/9954564/video/767157210) - M. Grey & Yadunund Vijay, Open Robotics @ ROSCon 2022 ([slides](http://download.ros.org/downloads/roscon/2022/How%20custom%20tasks%20are%20defined,%20assigned,%20and%20executed%20in%20Open-RMF.pdf))
- [JdeRobot VisualStates: Visual tool for generating automata based robot behaviors](https://vimeo.com/293530044) - Okan Asik, JdeRobot @ ROScon 2018 Lightning Talks ([repo](https://github.com/JdeRobot/VisualStates)).
- [NEXUS: A ROS 2 framework for orchestrating industrial robotic lines and cells](https://vimeo.com/879001338/fb3bcc8741) - Dejanira Araiza-Illan, Johnson & Johnson @ ROSCon 2023 ([slides](https://roscon.ros.org/talks/NEXUS_A_ROS_2_framework_for_orchestrating_industrial_robotic_lines_and_cells.pdf)).
- [PackML2: State Machine Based System Programming, Monitoring and Control in ROS2](https://vimeo.com/378683073) - Dejanira Araiza-Illan, ROS-Industrial Consortium Asia Pacific @ ROScon 2019 ([slides](https://roscon.ros.org/2019/talks/roscon2019_packml2.pdf)).
- [SMACC2, an open-source, event-driven, asynchronous, behavioral state machine library for ROS2 applications written in C++](https://vimeo.com/649655394/f9b25be7f9) - Brett Aldrich, ROBOSOFT AI @ ROScon 2021.
- [System Modes - model-based run-time state management of large systems](https://vimeo.com/767165876) - Ralph Lange, Bosch Research @ ROScon 2022 ([slides](http://download.ros.org/downloads/roscon/2022/System%20Modes%20-%20model-based%20run-time%20state%20management%20of%20large%20systems.pdf)).

## Papers and Book Chapters

- [CoSTAR: Instructing collaborative robots with behavior trees and vision](https://ieeexplore.ieee.org/document/7989070) - Chris Paxton et al.
- [Extended behavior trees for quick definition of flexible robotic tasks](https://ieeexplore.ieee.org/document/8206598) - Francesco Rovida et al.
- [KnowRob: A knowledge processing infrastructure for cognition-enabled robots](https://journals.sagepub.com/doi/abs/10.1177/0278364913481635?journalCode=ijra) - Moritz Tenorth et al.
- [Optimized Execution of PDDL Plans using Behavior Trees](https://arxiv.org/abs/2101.01964?s=08) - Francisco Martín et al.
- [Robotic Systems Architectures and Programming in the Handbook of robotics](https://link.springer.com/book/10.1007/978-3-540-30301-5) - David Kortenkamp, Bruno Siciliano et al.
- [SkiROS—A Skill-Based Robot Control Platform on Top of ROS](https://link.springer.com/chapter/10.1007/978-3-319-54927-9_4) - Francesco Rovida et al. (SkiROS is superseeded by SkiROS2)

## Blog Posts

- [Integrated Task and Motion Planning in Robotics](https://roboticseabass.com/2022/07/30/integrated-task-and-motion-planning-in-robotics/) - Sebastian Castro, 2022.
- [Introduction to Behavior Trees](https://roboticseabass.com/2021/05/08/introduction-to-behavior-trees/) - Sebastian Castro, 2021.
- [Task Planning in Robotics](https://roboticseabass.com/2022/07/19/task-planning-in-robotics/) - Sebastian Castro, 2022.

## Podcasts

- [Can One Person Make Two Powerful Tools for the Robotics Community?](https://www.sensethinkact.com/episodes/26-davide-faconti) - With Davide Faconti, author of BehaviorTree.CPP.
- [ROS Plan](https://www.theconstructsim.com/rdp-047-ros-plan-michael-cashmore/) - RDP 047 with Gerard Canal and Michael Cashmore.
- [State Machines for Complex Robot Behavior](https://www.sensethinkact.com/episodes/10-brett-aldrich) - With Brett Aldrich, author of SMACC2.
- [Towards Assured Robot Autonomy with ROS](https://www.theconstructsim.com/100-towards-assured-robot-autonomy-with-ros-with-patrick-musau/) - RDP 100 with Patrick Musau.

## Demos

- [CoSTAR: Instructing Collaborative Robots with Behavior Trees and Vision](https://www.youtube.com/watch?v=eGdwl1dmTrA) - CoSTAR demos like sanding, pick & place and robot instruction.
- [Dual-arm Piston Insertion](https://www.youtube.com/watch?v=sTM0ih6faMs) - Piston insertion with kinesthetic teaching, vision, task adaption & knowledge integration.
- [Robot Household Marathon: EASE Generative Models of Everyday Activity](https://www.youtube.com/watch?v=pv_n9FQRoZQ&t=4s) - Setting a table with a PR2.
- [Simulation of Robot using Behavior Tree](https://www.youtube.com/watch?v=a0ve2CH245Y) - MOOD2BE, part of Robmosys.
- [TurtleBot 3 Behavior Demos](https://github.com/sea-bass/turtlebot3_behavior_demos) - Examples of behavior trees for navigation actions in C++ and Python.
