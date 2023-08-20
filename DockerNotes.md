## What are containers ?
Containers are lightweight, portable, and isolated software environments that allow developers to run and package applications with their dependencies, consistently across different platforms


## How do containers works?
Unlike traditional virtualization, which emulates a complete operating system with its hardware resources, containers share the host’s OS kernel and leverage lightweight virtualization techniques to create isolated processes. This approach leads to several benefits, including:

`Efficiency`: 
Containers have less overhead and can share common libraries and executable files, making it possible to run more containers on a single host compared to virtual machines (VMs).

`Portability`:
Containers encapsulate applications and their dependencies, so they can easily be moved and run across different environments and platforms consistently.

`Fast startup`:
Since containers don’t need to boot a full OS, they can start up and shut down much faster than VMs.

`Consistency`:
Containers provide a consistent environment for the development, testing, and production stages of an application, reducing the “it works on my machine” problem.


## Containers and Docker
Docker is a platform that simplifies the process of creating, deploying, and managing containers. It provides developers and administrators with a set of tools and APIs to manage containerized applications. With Docker, you can build and package application code, libraries, and dependencies into a container image, which can be distributed and run consistently in any environment that supports Docker.



## Why do we need containers?
In the world of software development and deployment consistency and efficiency are crucial... so what are the problems that containers came to solve?

- `Inconsistent environments`: Developers often work in different environments which might have different configurations and libraries compared to production servers. This leads to compatibility issues in deploying applications.

- `Inefficient resource utilization`: Virtual Machines (VMs) were widely used to overcome environmental inconsistency. However, VMs require an entire OS to be running for each application, making the resource utilization inefficient.

- `Slow processes and scalability issues`: Traditional deployment methods have a slower time to market and scaling difficulties, which hinders fast delivery of software updates.










