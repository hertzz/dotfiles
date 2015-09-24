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

### Usage

Run the playbook:
```shell
$ ./bin/run [playbook]
```

Run a specific role:
```shell
$ ./bin/run [playbook] [role]
```

If no first argument is specified, the `osx.yml` master playbook will be used.

### Contributors
See [CONTRIBUTORS.md](CONTRIBUTORS.md) for more info.

### License
See [LICENSE.md](LICENSE.md) for more info.
