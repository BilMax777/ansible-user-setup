# Ansible Playbook with Roles

This Ansible project creates groups and users on remote hosts, assigns them passwords, adds SSH keys for remote access, and ensures that users change their password after their first login.

## Project Structure

ansible
    ├───group_vars
    │   └───all
    └───roles
        ├───groups
        │   ├───tasks
        │   └───vars
        └───users
            └───tasks