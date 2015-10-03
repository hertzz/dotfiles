## Dotfiles

This repository contains roles for Ansible which are used to configure various parts of OS X and applications across my
Apple computers. The playbook has been tested against OS X Yosemite (10.10.x) and El Capitan (10.11.x).

### Installation

Install pip/ansible:
```shell
$ sudo easy_install pip
$ sudo pip install ansible --user $USER
```

### Usage

Run the playbook:
```shell
$ ./bin/run [ROLE]
```

Run a specific playbook role:
```shell
$ ./bin/run homebrew
```

### Roles

* atom
    * Provides management of core/custom packages for use with GitHub Atom IDE
* common
    * Provides management of OS X defaults
    * Provides management of Safari defaults
    * Installs XCode/XCode CLI utils
* git
    * Provides management of Git CLI properties (global .gitignore, .gitconfig etc...)
* homebrew
    * Provides management of Homebrew environment setup
    * Provides management of Homebrew packages & taps
    * Package specific updates/upgrades and internal brew updates
* vim
    * Provides management of global VI configuration (.vim)
    * Provides management of VI colors and syntax plugins/themes
* zsh
    * Provides management of zsh plugins/themes

### Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) for more info.

### Contributors
See [CONTRIBUTORS.md](CONTRIBUTORS.md) for more info.

### License
See [LICENSE.md](LICENSE.md) for more info.
