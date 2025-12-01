# netbox-inventory-repo

# NetBox Dynamic Inventory for AWX / Ansible

This repository contains a minimal configuration to allow AWX or Ansible
to dynamically pull inventory from a NetBox Source of Truth (SoT).

## Contents
- `inventory/netbox_inventory.yml` — NetBox inventory plugin file
- `requirements.yml` — Required Ansible collections
- `.gitignore` — Standard ignore file

## Usage (Local Test)

1. Install dependencies:

   ```bash
   ansible-galaxy collection install -r requirements.yml
   pip install pynetbox
