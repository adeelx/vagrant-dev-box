# General purpose Vagrant box

For now, have a look at `site.pp` to see whats included.

## Building the box

```terminal
rake rebuild
```

This will output a box named like `quantal64-dev-box-2013-01-23.box` that you can
add to vagrant with `vagrant box add quantal64-dev-box-2013-01-23 /path/to/quantal64-dev-box-2013-01-23.box`.

Please note that it takes ~20/25 minutes to rebuild the VM on my laptop using
a 15mb connection, so go grab a coffee while it runs ;)

I keep the latest release on a public folder at my dropbox account, feel free to
use it:

```terminal
vagrant box add quantal64-rails-2013-01-23 http://dl.dropbox.com/u/13510779/quantal64-dev-box-2013-01-23.box
```
