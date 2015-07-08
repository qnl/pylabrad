pylabrad
========

[![Build Status](https://secure.travis-ci.org/labrad/pylabrad.png)](http://travis-ci.org/labrad/pylabrad)
[![Coverage Status](https://coveralls.io/repos/labrad/pylabrad/badge.svg)](https://coveralls.io/r/labrad/pylabrad)

pylabrad is an interface to the LabRAD system in python with support for both clients and servers.
For general information about the LabRAD system/protocol see [the labrad repository](https://github.com/labrad/labrad) and associated [wiki](https://github.com/labrad/labrad/wiki).
For help getting started and understanding pylabrad take a look at the [wiki](https://github.com/labrad/pylabrad/wiki).

Contributing
------------

### Code

For instructions on how to contribute to pylabrad, see [contributing.md](https://github.com/labrad/pylabrad/blob/master/contributing.md).

### Documentation

We use the github wiki for documentation.
If you have commit access, just edit the wiki, no pull request needed.
If you do not have commit access, please file an issue and add the `doc/wiki` tag.
We really appreciate contributions to help improve the documentation!

Migration note
--------------

This repo was moved from the martinisgroup organization.
To tell git to pull updates from the new location, you'll
want to update the 'origin' remote in your local repository.
Use `git remote -v` to see the names and urls for all remotes
you have defined, then `git remote set-url` to update the url,
changing the organization to labrad:

```
$ git remote -v
origin	git@github.com:martinisgroup/pylabrad (fetch)
origin	git@github.com:martinisgroup/pylabrad (push)

$ git remote set-url origin git@github.com:labrad/pylabrad
```

Tips
----

Did you know about the LabRAD Node? It's super cool!
Start it easily with the labradnode.py script in the
scripts folder.


Credits
-------

```
PyParsing Copyright (c) 2003-2007  Paul T. McGuire
```

```
unwrap.py from http://www.wave.co.nz/~glyn/
```
