# Install a webserver from module

## Install a module

```
sudo apt install puppet-module-puppetlabs-apache -y
cd /usr/share/puppet/modules.available/puppetlabs-apache
tree
```

## Create a webserver.pp & install it

```
cd
vi webserver.pp
include ::apache
```
