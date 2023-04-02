# Performance Monitoring and Automated Container Recovery of 5G Core Network Deployments
SYSC 5804 5G Ansible project for the Winter 2023 term.


## Project Description
This project aims to investigate the use of automation in monitoring and managing 5G core
network deployments. 

The goal of this project is to explore the use of containerization in the deployment of 5G networks and develop enhancements related to container health monitoring and automatic recovery. The enhancements shown as part of this project focused on improving 5G core network deployment reliability through the integration of various software tools and offering 5G core network performance monitoring. The enhancements include being able to automatically restart 5G core network function containers in the event of a recoverable failure, and in the event of an unrecoverable failure on a node, the ability to move those 5G core network container functions to another available node in the cluster.

The 5G core network repository used in the project is the OpenAirInterface5G repo provided by the OpenAirInterface software alliance. This repository provides Docker images of different 5G core network functions, as well as configuration files that can be used to deploy the core network functions as Docker containers. In the following sections, information about the tools that were integrated together in order to achieve the project enhancement goals of improved 5G core network reliability and performance monitoring is outlined. In addition, scenarios demonstrating the implementation and usefulness of these enhancements are also shown.

## Step-by-step documentation to replicate project environment
* Setup Docker Container VM [documentation](documents/setup-docker-vm.md)

* Setup Zabbix Server VM [documentation](documents/setup-server-vm.md)

## PowerPoint Presentation
* [PowerPoint Presentation](documents/5GAnsibleProject.pptx)

## Helpful Reference documents
* [Useful Links](documents/useful-links.md)


## Credits
* [OpenAirInterface](https://openairinterface.org/)
* [Zabbix](https://www.zabbix.com/)
* [Ansible](https://www.ansible.com/)
* [Docker](https://www.docker.com/)
* [Digital Ocean](https://www.digitalocean.com/)
* [Oracle VirtualBox](https://www.virtualbox.org/)