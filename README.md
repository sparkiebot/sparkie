![](/media/sparkie_01.png)
# Overview

Sparkie is a robot intended to be used as a platform for learning and experimentation. It is designed to entirely be 3D printed and assembled from scratch.
It will be able to help people in some daily tasks, such as patrolling, control smart home appliances, remind you of important events, and much more.
Sparkie is entirely 3D printed and assembled from scratch. 

# Other documentation

- [Bill of Materials](/docs/bom.md)
- [Architecture](/docs/architecture.md)
- [Build Guide](/docs/setup/build.md)
- [Software Installation Guide](/docs/setup/software.md)
- [Usage Guide](/docs/usage.md)

# Showcase
![](/media/sparkie_rotating.gif)

# Bill of Materials

To build Sparkie, you will roughly need:
- A 3D printer or access to one
- A Jetson Orin board
- A RealSense camera (D435x), or any other 3D camera (you will need to modify the camera mount and relative software).
- A Lidar sensor (Slamtec RPLidar C1)
- Some components (raspberry pico, battery, motors, switches, etc)
- Some screws, nuts, and bolts
- A custom printed circuit board (PCB) to connect all the components

If you want a detailed list of all the components with corresponding links, you can check the [Bill of Materials](/docs/bom.md) file.

# How to build

To get started building Sparkie, refer to the [build guide](/docs/setup/build.md).

# Usage

After you successfully built Sparkie, you will need to install the software on the Jetson Orin board. To do so, refer to the [software installation guide](/docs/setup/software.md).

Once you have installed the required software, you can start using Sparkie.
Right now you will have to manually start Sparkie software and you will be required to develop your own software to interact with Sparkie.
However, in the future, there will be a more user-friendly way to interact with Sparkie.

If you want to know more about how to use Sparkie, refer to the [usage guide](/docs/usage.md).

# Expanding Sparkie

In the future there will be the possibility to expand Sparkie with additional features. If you want to know more about how to expand Sparkie, refer to the [expansion guide](/docs/expansion.md).

# Contributing

If you want to contribute to the project, you should create a pull request on the specific repository you want to contribute to.