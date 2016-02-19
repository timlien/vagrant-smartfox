# vagrant-smartfox

[SmartFox Server 2x][1]  Development Environment


## Installation
Install [Vagrant][2] and its dependencies.

Download vagrant-smartfox to your local directory.
```bash
$ cd /path/to/local/vagrantfile
$ vagrant up
```


## Usage
You can the visit the following admin URL in a browser.

The default username/password is sfsadmin/sfsadmin.
```
http://localhost:8080
```

Put your SmartFox Server extension into extensions directory.


## Log

SmartFox Server log
```bash
$ cd /path/to/local/vagrantfile
$ vagrant ssh
$ docker exec -it vagrant_smartfox cat /var/SmartFoxServer_2X/SFS2X/logs/smartfox.log
```

[1]: http://www.smartfoxserver.com/
[2]: https://www.vagrantup.com/