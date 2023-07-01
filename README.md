<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Ansible_Logo.png" alt="Ansible Logo">
</p>

<h1 align="center">Ubuntu/Fedora Server Setup using Ansible</h1>

## Introduction

This repository contains Ansible playbooks and configurations to automate the setup of Ubuntu and Fedora servers.

## Features

-   Update package repositories and perform system updates.
-   Install essential packages and dependencies.
    -   htop
    -   vim
    -   git
    -   fish
    -   sudo
-   Configure system timezone.
    -   Asia/Kolkata
-   Create a user account and set password.
-   Grant sudo privileges to the user.
-   Install Docker and Docker Compose.

## Usage

1. Update Repository and Install ansible:

```bash
  apt update && apt install ansible
```

2. Run the Ansible playbook using the following command:

```bash
ansible-pull -U https://github.com/pranjalmaurya01/ansible-deb.git
```
