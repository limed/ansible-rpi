## ansible-rpi
This is an ansible playbook to setup my raspberry pi's the use case is very specific to mine (limed) and therefore no one else should really use this

## How to run
I use docker to do run this, because I don't want to install sshpass and ansible locally

```
# docker pull williamyeh/ansible:ubuntu16.04
# cd ansible-rpi
# docker run -it -v ${PWD}:/mnt -v ~/.ssh/:/root/.ssh williamyeh/ansible:ubuntu16.04 /bin/bash
```
