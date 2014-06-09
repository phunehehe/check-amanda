check-amanda
============

This is now deprecated. Use the [Amanda cookbook][3] instead.

`check_amanda.py` is a script that tries to restore a random file from an
Amanda backup of a random disk of a random host using a random backup set. It
expects in `/etc/chef/node.json` parameters suitable for the [amanda module of
chef-cookbooks][1].

Some notes about the initial release can be found in [Checking Amanda
Backups][2].

[1]: https://github.com/phunehehe/chef-cookbooks/tree/master/amanda
[2]: https://phunehehe.net/checking-amanda-backups/
[3]: https://github.com/phunehehe/chef-cookbooks/tree/master/amanda
