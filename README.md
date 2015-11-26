# README.md
# Ansible Role: mats116.awscli

An Ansible role that installs awscli on **Ubuntu 14.04 LTS**

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

    awscli_install_dir: /usr/local/aws
    awscli_bin_location: /usr/local/bin/aws

## Dependencies

none

## Example Playbook

    - hosts: ec2-server
      roles:
        - role: mats116.awscli
          awscli_install_dir: /opt/aws

## License

MIT
