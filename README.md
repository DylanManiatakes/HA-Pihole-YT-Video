This Project is a simple put together solution for a Hilghy Avalible PiHole solution
We will use Keepalived to act as a load-balancer and failover solution for the PiHole web interface
We will use Orbital Sync - https://github.com/mattwebbio/orbital-sync to keep the PiHole web interface up and running
Use the Docker Compose file to spin up the Docker containers for Orbital Sync
Use the conf file as a template for Keepalived.

YouTube Content and Script to Come

// YouTube Content 

Highly Available Pi-hole DNS Setup with Orbital Sync and Keepalived
Welcome to the guide for setting up a highly available Pi-hole DNS solution using Orbital Sync and Keepalived. This setup ensures that if one Pi-hole instance goes down, the other seamlessly takes over, maintaining DNS availability without interruption.

Overview
In this project, we:

Set up multiple Pi-hole instances (in containers or VMs)
Use Orbital Sync to keep DNS configurations synchronized across instances
Install and configure Keepalived to manage failover with a virtual IP (VIP)

Requirements:
    2x Virtualization Platform or Hardware Pi-hole instance
    Docker somewhere
    OrbitalSync from GitHub: https://github.com/mattwebbio/orbital-sync
    Keepalived package for failover
    Two Pi-hole instances (physical or virtual machines)
