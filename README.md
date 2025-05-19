

<p align="center">
    <img src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/ansible.png" alt="Ansible" width="120" height="120">
</p>

# Ansible summary practice

## Overview

This project contains practice from page 85 from "Ansible shallow dive pdf"

## Requirements

- Python 3.8 or higher
- Ansible 2.9 or higher
- Git

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/ansible-shallow-dive.git
    cd ansible-shallow-dive/homework
    ```

2. **Install Ansible:**  
    You can install Ansible using one of the following methods:

      - **Ubuntu/Debian:**
         ```bash
         sudo apt update
         sudo apt install ansible
         ```
      - **Rocky/RHEL:**
         ```bash
         sudo dnf install epel-release
         sudo dnf install ansible
         ```

3. **Run playbook:**  
   - ansible-playbook playbook.yml

## Structure

- `playbook.yml` — Ansible playbook
- `hosts.ini` — Inventory file with list of all hosts
- `ansible.cfg` — Ansible basic configuration

## License

This project is licensed under the MIT License.

## Author

- Dmitri Donskoy
- crooper22@gmail.com

