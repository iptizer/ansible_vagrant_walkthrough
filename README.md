## Ansible + Vagrant = WordPress 

This repository is a very simple example to show how Ansible and Vagrant work together. WordPress has been chosen because it's a not too simple service to deploy that everyone is familiar with.

I created this for a Meetup. Feel free to contact me. You can find the slides [inside this repo by clicking here](ansible_walkthrough.pdf).

### How to use

Inside this repositories root simply execute:

```bash
vagrant up
ansible-playbook site.yml
```

After that you can hit the webbrowser at the following address: [http://127.0.0.1:8080](http://127.0.0.1:8080)