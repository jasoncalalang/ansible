# Ansible Repository

## Description

This repository contains Ansible playbooks and configurations to automate the hardening of RHEL 9.4 images. It includes tasks for system hardening, compliance checks, and generating CIS (Center for Internet Security) reports.

## Usage

1. **Clone this repository in your Ansible VSI:**
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Update the inventory file:**
    - Edit the `inventory` file to include the target hosts and necessary variables.

3. **Run the Ansible playbook:**
    ```sh
    ansible-playbook -i inventory playbooks/playbook.yaml
    ```

4. **Extract the CIS report:**
    - After the playbook execution, the CIS report will be available in the `playbooks/reports` folder.

## Additional Information

- Ensure that you have the necessary permissions and access to the target hosts.
- Verify that all required Ansible roles and dependencies are installed.
- Customize the playbook and inventory file as per your environment and requirements.
