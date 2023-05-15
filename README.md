
# Deploy nexus using Ansible


# Prerequisites

Before you begin, you will need the following:

 1- An AWS account

 2- A remote server (ec2) running an Ubuntu operating system

 3- Ansible installed on your local machine

 4- A configured SSH connection to the remote server

 
 # Playbook Overview
 The Ansible playbook consists of two roles:

1- Prerequisites

This role installs the necessary packages and dependencies for running Nexus, including Java.

2- Nexus

This role deploys and configures Nexus on your remote server ec2 on aws.










