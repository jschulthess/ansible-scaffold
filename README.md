# ansible-scaffold
Basic Ansible files for running a playbook

## Introduction

Ansible is great for quickly creating a playbook or to run some ad-hoc commands.
Most of the time this needs some minimal files to locally define Ansible default,
 and inventory or similar scaffold.

This repository contains scaffold files with options that might be helpful to
get up and running quickly.

## Usage

1. Clone the repository, eg.

   ```
   git clone https://github.com/jschulthess/ansible-scaffold
   ```

2. run ansible commands from within the clone directory, eg.

   ```
   cd ansible-scaffold
   ansible-playbook pb-hello.yml
   ```
