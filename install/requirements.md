---
title: Requirements
description: System and software requirements for this datapack to run on a server.
published: true
date: 2020-05-17T22:02:45.360Z
tags: 
---

# Datapack Requirements
This datapack is designed to be as light as possible on servers. That being said it still must put a slight load on servers to be able to run. These requirements are the minimum recommended requirements to host a game with 8 players. As the player count increaess so should the hardware allocations. Keep an eye on resource usage and increase as necessary.

## Software
I recommend PaperMC as your server application. See the [PaperMC](#papermc). As with any Minecraft server you will need Java as well. 

## Hardware
Hardware requirements will differ based on server application as some are more optimized than others. 

#### Recommended Regardless of Applicaiton
* SSD boot or storage drive. NVMe is ideal but SATA will work just fine.
	* Around 10GB of free space recommended as the world will get larger over time.
* 4+ Core CPU with good IPC (Intel i5 or i7, or any modern AMD Ryzen)
* 4GB+ of RAM, ideally 8GB+
	* The faster the RAM the better

### Vanilla
*Untested*

### Spigot
*Untested*

### PaperMC
PaperMC is a highly optimized fork of the Minecraft server code. It greatly increases server performance and is my personal recommended way to run any Minecraft server. It support spigot plugins and adds useful commands to monitor the server performance. Download it here: [PaperMC](https://papermc.io/ "PaperMC Home")

#### Minimum
* CPU: 2 Cores
* RAM: 4GB

#### Recommended
* CPU: 4 Cores
* RAM: 8GB

# My Setup
I have been developing and running this datapack without issues with 4 cores allocated and 4GB of RAM. I have running it inside of a VM in Proxmox, and using [Pterodactyl Panel](https://pterodactyl.io/ "Pterodactyl Panel Home") to manage my servers. The specs are as follows:
* CPU: Intel Core i7-3770 (4C/8T) | VM has access to all 8 threads
* RAM: 24GB DDR3-1660Mhz | 12GB allocated to VM
* Storage: 500GB Samsung EVO 860 SSD
### Server Allocations
* CPU: 4 cores
* RAM: 4GB
* Storage: 10GB