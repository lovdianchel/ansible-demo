# Ansible Demo

### Requirements
Software :
- python
- pip

### Installation

Install Ansible :
```sh
$ pip install ansible
```

### Setup Inventory
Change [your_host] to your Ansible Slave IP or Domain, and change [url] to your static website git repository.
```sh
[webservers]
your_host git_repo="url"
```
Example:
```sh
[webservers]
192.168.43.1 git_repo="https://github.com/lovdianchel/first-pwa-dicoding.git"
```

You can add another host as many as possible:
```sh
[webservers]
your_host1 git_repo="url"
your_host2 git_repo="url"
your_host3 git_repo="url"
your_host4 git_repo="url"
your_host5 git_repo="url"
```
