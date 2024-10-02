# 4D-Qubes-Nexus-OS
or "TetraQubes OS"

A Reasonably Extra Secure Operating System
by NixOS and Qubes OS

4-dimensional Qubes OS fork. QubesOS =3D . +1D = NixOS container structure. 4D = NixOSs in Qubes OS. 

  A Qubes OS fork symbolizing 4-dimensional cubes. The cubes symbolize virtual machines. NixOS can be installed on each cube. Thus, the container layer of NixOS is included in the cubes, changing the cubes from 3D to 4D. +1D = NixOS container structure. This creates 4D Qubes Nexus OS, which are four-dimensional cubes. Colloquially called TetraQubes OS, it is a project that aims to provide a secure and modular operating system structure by combining Qubes OS and NixOS. A reasonably extra secure operating system.  In this project, virtual machines in Qubes OS will run with NixOS by default; and dependencies and packages will be isolated within containers in this NixOS environment. Thanks to this structure, a 4-dimensional layered architecture will be created:
  1. Qubes OS - A split operating system for security.
  2. Virtual Machines (VMs) - Each isolated and running with NixOS.
  3. NixOS - Modular and reliable operating system running inside virtual machines.
  4. Containers - A structure within NixOS where dependencies and packages are run in isolation.

This architecture aims to maximize system security while offering significant improvements in modularity and manageability.



Project Objective

Using the secure and isolated virtual machine infrastructure offered by Qubes OS, we are unifying the modular building blocks of NixOS. Thanks to this project, every virtual machine will work with NixOS and thousands of dependencies and packages within each NixOS will be managed through containers.

This structure aims to increase system security, ease manageability and modular availability of packages. By combining the strong security architecture of Qubes OS with the dependency management capabilities of NixOS, cross-system harmonization will be achieved.

Layers of Architecture

  1. Qubes OS: Enhances security by providing complete isolation between the host system and virtual machines.
  2. NixOS VMs: Each virtual machine is powered by NixOS and managed independently.
  3. Containers: Within NixOS, dependencies, packages and services are isolated and controlled through containers.

Advantages

  1. Security The virtual machine isolation offered by Qubes OS maximizes the security of the system.
  2. Modularity: Thanks to the configurability of NixOS, virtual machines and their packages can be built in a completely flexible and modular structure.
  3. Isolated Dependencies: Containers ensure that dependencies are managed independently of each other and the integrity of the system is maintained.
  4. High Manageability: The modular configuration and declarative nature of NixOS makes system administration very easy.

Project Objectives

    Ensure NixOS is installed by default on Qubes OS virtual machines.
    Optimize package and dependency management through containers on NixOS.
    Provide multi-layered security and manageability by creating a secure and isolated architecture.
    Enabling different software environments to run independently on the same system.

How Can You Contribute?

If you would like to contribute to this project, please follow the steps below:

    Develop after forking the repository.
    Create pull requests to add new features or fix bugs.
    Share your feedback by opening an issue.

License

This project is licensed under the MIT license. See the LICENSE file for details.
