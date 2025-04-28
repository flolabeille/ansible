# ROLE COMMON

Basic configuration common to all servers (security, updates, users)

- ~~files~~
- ~~handlers~~
- **tasks** :
  `main.yml` download and install updates, configure security firewall rules

- ~~templates~~
- **vars** :
  `Debian_Family.yml` & `Redhat_Family.yml` download and install updates set a non exhaustive list of package to install by default on Redhat families distributions. Redhat, Rocky Linux.
