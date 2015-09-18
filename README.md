## OS X SOE Playbook

### Getting started

Install pip/ansible:
```shell
$ sudo easy_install pip
$ sudo pip install ansible
```

Create ansible hosts file:
```shell
$ sudo mkdir -p /etc/ansible
$ sudo echo "127.0.0.1" > /etc/ansible/hosts
```

OR

```shell
$ sudo bash <(curl https://raw.githubusercontent.com/hertzz/osx-soe-playbook/master/bin/install -L)
```

### Usage

Run the `ansible-playbook` command:
```shell
$ sudo ansible-playbook osx-soe-playbook/osx.yml
```

### Contributors
See [CONTRIBUTORS.md](CONTRIBUTORS.md) for more info.

### License
See [LICENSE.md](LICENSE.md) for more info.
