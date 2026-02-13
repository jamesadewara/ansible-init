# Why Ansible? - Automation Project

This repository contains the configuration files for the tutorial: **[Why Ansible?. Ansible is an agentless automation tool…](https://medium.com/@jamesadewara/why-ansible-ansible-is-an-agentless-automation-tool-0f461664154c)**.

## Project Overview
The goal of this project is to demonstrate how to use Ansible, an agentless automation tool, to manage server configurations efficiently. By following the associated Medium article, you will learn how to set up infrastructure automation using the provided playbook.

## Repository Contents
* `inventory.ini`: Defines the target hosts/nodes that Ansible will manage.
* `playbook.yaml`: Contains the list of tasks to be executed on the managed nodes.

## How to Use
1.  **Clone the repo:**
    ```bash
    git clone https://github.com/jamesadewara/ansible-init.git
    cd ansible-init
    ```
2.  **Update the inventory:** Edit `inventory.ini` to match your server's IP addresses and credentials.
3.  **Run the playbook:**
    ```bash
    ansible-playbook -i inventory.ini playbook.yaml
    ```

For a detailed step-by-step guide, please refer to the [Medium Article](https://medium.com/@jamesadewara/why-ansible-ansible-is-an-agentless-automation-tool-0f461664154c).
