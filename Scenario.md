



# All u need to know about this project!

## What it uses

- Ansible
- Ubuntu Server 18.04
- Host machine with ansible
- another machine with SSH access for running playbook to
- docker-compose
- docker
- GitLab/GitHub

## What we don't provide

- shell commands
- ways to deploy ssh keys
- preparing servers
- installing ansible
- actual app for running with docker (we used something similar to a notes-taking app)

## What it does:

### GitLab / GitHub

- pulling your repos via HTTPS
- including tokens
- building images locally
  - assigning versions to newly bult images via assigned variable inside playbook

### Ansible

- running ansible
- 3 different roles
  - with own tasks
- using a vault
- SSH connection to server
  - it's up2u, but we created with cools the ssh pub key locally(on the ansible machine) and deployed it via ssh to server for securing connection
- 1 playbook
- tags for uninstalling / removing files 
- install docker & docker-compose on remote server

### Docker

- building images

- running docker-compose

- using templates for generating docker-compose with variables

- run / stop / delete containers

- install/uninstall docker & docker-compose

  

## Variables: 

I had to anonymize the whole project because of rules.

- fsdst, where all the things shall be stored on the local file system
- app, not everywhere (sometimes an attribute) but the name which specifies your application.
- tokenhere, for your token to pull/clone your Gitlab/GitHub Repo.
- ****, usernames, Domains - all I had to anonymize.
- "*"username"*" , username for service running on server.

