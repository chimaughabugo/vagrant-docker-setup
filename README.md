# Vagrant Docker Setup

This repository contains a Vagrant configuration file for provisioning an Ubuntu virtual machine with Docker and Docker Compose installed. The setup is designed for local development and testing environments.

## Features

- Ubuntu 20.04 LTS (`ubuntu/focal64`)
- Docker Engine
- Docker Compose
- Private network configuration (IP: `192.168.56.82`)
- Public network support (bridged)
- VirtualBox provider with 2GB memory

## Prerequisites

- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/)

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/chimaughabugo/vagrant-docker-setup.git
   cd vagrant-docker-setup
