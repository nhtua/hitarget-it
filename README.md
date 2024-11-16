# Hello my targets! - HiTarget

**hitarget-it** is an Ansible playbook collection for HiTarget configuration and deployment. `hitarget` was design with 3 main components: 

- [hitarget-api](https://github.com/nhtua/hitarget-api): the backend api is written in Python 3.6 using FastAPI, which processes all logic of this TODO list app
- [hitarget-ui](https://github.com/nhtua/hitarget-ui): the frontent UI is written in Javascript using VueJs 3.x
- [hitarget-it](https://github.com/nhtua/hitarget-it): the configuration and deployment management scripts using Ansible Playbook

## Requirements

- Localhost is runnig with a Linux distribution, suggest Ubuntu or Arch (Btw, I use Arch).
- Two remote servers; one will be used for web-server; one other will be used for MongoDB.

## Server connections

- Update Ip of two remote servers in [_inventory.ini](./_inventory.ini)
- Update path to SSH private key to each server in _inventory.ini as well

Test connections by running
```
ansible -m shell -a "date" all
```
This command shows time on all connected server

## Configure servers
(to be added)

## Deploy apps
(to be added)


## Ceavats
I have not been working on this project for a long time. It was just one of my experiment. So configuration and versions may be already outdated. I write down here all from memory. If you are interested, give me question or open PR. I still can help to answer or review.
