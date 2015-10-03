# Contributing

If you find this Ansible playbook useful, feel free to fork the repository and add some new functionality. Once you are satisfied that your changes work correctly and have been tested against OS X Yosemite (10.10.x) and El Capitan (10.11.x), send a pull request with a summary outlining the changes. Please ensure that you do not commit any personal information or files specific to your own system setup (i.e. git credentials, SSH RSA keys etc...)

## Notes

* Be very careful when testing out changes using the `common` role to modify OS X system defaults as you can potentially temporarily lock yourself out of your system. (If this does happen, you can boot into recovery mode and remove the problematic domain plist file(s)).
