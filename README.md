# Ansible setup for Raspberry Pi

This project provides an Ansible playbook for setting up a Raspberry Pi.

## Features
- Installs docker
- Installs docker-compose
- Installs unifi controller
- Installs tailscale (as subnet router)

## Getting Started

To use this playbook, you'll need to have Ansible installed on your local machine. You'll also need to have a Raspberry Pi with SSH access enabled.

1. Clone this repository to your local machine.
2. Update the `inventory.yml` file with the IP address of your Raspberry Pi.
3. Update the `defaults/main.yml` file with the configurations and packages you want to install.
4. Run the playbook using the command `ansible-playbook main.yml -u <<username>>`.
