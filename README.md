# xampp-cli
>Command line interface for easier control XAMPP

## Installation
Open your `Terminal`, go to folder where you downloaded **xammp-cli** and run `sh ./installer`:
```bash
cd /path/to/xampp-cli
sh ./installer
```

## Help
If you need help, open `Terminal` and type `xampp` without arguments. Available commands:
* **add** - adds a new host from existing folder (Usage: `sudo xampp add <domain> [path/to/project]`). If directory `path/to/project` doesn't exist, it will be created. If you run this command with one argument, a new host will be added from a folder that has the same name (Usage: `sudo xampp add <domain>`). If directory `domain` doesn't exist, it will be created in current directory.
* **remove** - removes host from XAMPP (Usage: `sudo xampp remove <domain>`). That command removes host from `/opt/lampp/etc/extra/httpd-vhosts.conf` and `/etc/hosts`, and removes symbolic link to project from `htdocs`.
* **gui** - runs `manager-linux.run` or `manager-linux-x64.run`.
* All default XAMPP commands (`start`, `startapache`, `startmysql`, `startftp`, `stop`, `stopapache`, `stopmysql`, `stopftp`, `reload`, `reloadapache`, `reloadmysql`, `reloadftp`, `backup`, `restart`, `security`, `oci8`, `enablessl`, `disablessl`).

## Contribution

If you find an error or have questions, please report to [issues](https://github.com/ziyaddin/xampp/issues).

## About

Copyright (C) 2019 Ziyaddin Sadigov ([@zsadigov](http://twitter.com/zsadigov)).
