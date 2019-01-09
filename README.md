# patchserver-ansible

## A simple ansible role/playbook to keep packages up to date on debian and redhat servers

## Setup

Create an inventory file and simply call `play.yml` using ansible-playbook! Ideally use a tool like cron or awx to automate this process often.

## Running

To run the playbook, simply call ansible-playbook like so:

    ansible-playbook -i inventory play.yml
