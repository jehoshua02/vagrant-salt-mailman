# From Scratch

+ [Python 2.7.5 should be installed](http://wiki.list.org/display/DOC/Installation+requirements)
+ [Apache package should be installed](http://list.org/mailman-install/node3.html)
+ [Postfix package should be installed](http://list.org/mailman-install/node3.html)
+ [`mailman` user should be present](http://list.org/mailman-install/node4.html)
+ [`mailman` group should be present](http://list.org/mailman-install/node4.html)
+ [`mailman` user should be member of `mailman` group](http://list.org/mailman-install/node4.html)
+ [Install directory `/usr/local/mailman` should exist](http://list.org/mailman-install/create-install-dir.html)
+ [Install directory group should be set to `mailman`](http://list.org/mailman-install/create-install-dir.html)
+ [Install directory permissions should be set `chmod a+rx,g+ws .`](http://list.org/mailman-install/create-install-dir.html)
+ [Source directory `/usr/local/mailman/src` should exist](http://list.org/mailman-install/create-install-dir.html)
+ [Source tarball should be downloaded and upacked to source directory](http://list.org/mailman-install/create-install-dir.html)
+ [Command `configure` should be run in source directory by a member of the `mailman` group](http://list.org/mailman-install/node7.html)
+ [Command `make` should be run in source directory by a member of the `mailman` group](http://list.org/mailman-install/node7.html)
+ [Command `make install` should be run in source directory by a member of the `mailman` group](http://list.org/mailman-install/node7.html)
+ [Command `bin/check_perms -f` should be run in the install directory by a member of the `mailman` group](http://list.org/mailman-install/node9.html)

([To Be Continued](http://list.org/mailman-install/node10.html))


# Package Manager

+ `sudo apt-get install mailman`