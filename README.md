# Project-One
Multi-tier Web App Setup,locally setup on laptop.
This multi-tier project will display an exiting website called 'VPROFILE' therefore, it can also be called VPROFILE PROJECT. This website contains frontend and backend services.The architecture for this project, contains the various services below.
Nginx - load balancer
Tomcat - Web App service - frontend
Memcache - Temporary memory cache
MySql - Backend storage service
RabbitMQ - Message broker like SQS service
The website is a social networking site already designed in java language. For this project, the website is accessed by an IP address which comes from the load balancer. So setting up the stack, it follows from
User - Ngnix - Tomcat - Memecache - MySQl  the rabbitmq is basically connected to the apache tomcat.

# Objectives
The objective of this projecct is to learn to setup up virtual machines locally;
- Baseline line for learning automation
- Enforce knowledge of manual automation before cloud computing
# Tools for local setup/ Automation tools
- Hypervisor - Oracle VM
- Automation - Vagrant
- CLI - Gitbash
- IDE - Sublime Text/ VSCode
In-order to implement the setup we connect the automation tools to communicate with the website services. So for the automation stack, vagrant will communicate the oracle VM box-hypervisor, with bash script or bash commands, we setup up the various website services.
