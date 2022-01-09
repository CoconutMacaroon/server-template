# Server template
This is a template for what files I tend to put on a server
## OS
This is designed for Debian 11
## Files
Here I describe every file and what it does
### `/etc/ssh/sshd_config`
Require modern and secure algorithms as per [SSH Audit](https://github.com/jtesta/ssh-audit). Also requires key-based authentication, instead of password auth.
