Docker Yumsync CHANGELOG
========================

The version numbers of this docker image do not directly reflect the
version number of Yumsync that is being used. Each image version below
will indicate what version of Yumsync it is using.

v1.3.0 (2017-05-10)
-------------------

* Bump Yumsync to version v1.3.0

| Yumsync |
| :-----: |
| [v1.3.0](https://github.com/jrwesolo/yumsync/tree/v1.3.0) |

v1.2.0 (2017-04-25)
-------------------

* Bump Yumsync to version v1.2.0

| Yumsync |
| :-----: |
| [v1.2.0](https://github.com/jrwesolo/yumsync/tree/v1.2.0) |

v1.1.1 (2017-04-13)
-------------------

* Bump Yumsync to version v1.1.1
* Install pip from pypa.io
* Build wheel and install with pip

| Yumsync |
| :-----: |
| [v1.1.1](https://github.com/jrwesolo/yumsync/tree/v1.1.1) |

v1.1.0 (2017-02-08)
-------------------

* Bump Yumsync to version v1.1.0
* Bump Gosu dependency to 1.10
* Change base image to `centos:7.3.1611`
* Set `WORKDIR` to data directory

| Yumsync |
| :-----: |
| [v1.1.0](https://github.com/jrwesolo/yumsync/tree/v1.1.0) |

v1.0.0 (2016-09-28)
-------------------

* Bump Yumsync to version v1.0.0

| Yumsync |
| :-----: |
| [v1.0.0](https://github.com/jrwesolo/yumsync/tree/v1.0.0) |

v0.5.0 (2016-09-15)
-------------------

* Bump Yumsync to version v0.4.0

| Yumsync |
| :-----: |
| [v0.4.0](https://github.com/jrwesolo/yumsync/tree/v0.4.0) |

v0.4.1 (2016-09-12)
-------------------

* Fix unnecessary slowness when starting container with a large data volume
* Split permissions fix into its own function and expose as mode
* Pin CentOS base image to centos:7.2.1511
* Bump gosu version to v1.9

| Yumsync |
| :-----: |
| [v0.3.0](https://github.com/jrwesolo/yumsync/tree/v0.3.0) |

v0.4.0 (2016-01-29)
-------------------

* Bump Yumsync to version v0.3.0

| Yumsync |
| :-----: |
| [v0.3.0](https://github.com/jrwesolo/yumsync/tree/v0.3.0) |

v0.3.1 (2016-01-28)
-------------------

* Bump Yumsync to version v0.2.1

| Yumsync |
| :-----: |
| [v0.2.1](https://github.com/jrwesolo/yumsync/tree/v0.2.1) |

v0.3.0 (2016-01-28)
-------------------

* Bump Yumsync to version v0.2.0

| Yumsync |
| :-----: |
| [v0.2.0](https://github.com/jrwesolo/yumsync/tree/v0.2.0) |

v0.2.2 (2016-01-27)
-------------------

* Bump Yumsync to version v0.1.4

| Yumsync |
| :-----: |
| [v0.1.4](https://github.com/jrwesolo/yumsync/tree/v0.1.4) |

v0.2.1 (2016-01-26)
-------------------

### Bugfix

* Bump Yumsync to version v0.1.3, this fixes a syncing error cause by incorrect parameters being passed from Yum to YumProgress. Refer to this [issue](https://github.com/ryanuber/pakrat/issues/3#issuecomment-175305140) for a detailed explanation.

| Yumsync |
| :-----: |
| [v0.1.3](https://github.com/jrwesolo/yumsync/tree/v0.1.3) |

v0.2.0 (2016-01-21)
-------------------

### Feature

* Restore and archive now show better time and percentage estimates

### Bugfix

* Bump Yumsync to version v0.1.2, this fixes combined metadata generation

| Yumsync |
| :-----: |
| [v0.1.2](https://github.com/jrwesolo/yumsync/tree/v0.1.2) |

v0.1.3 (2016-01-21)
-------------------

### Bugfix

* Do not overwrite archive file if it already exists

| Yumsync |
| :-----: |
| [v0.1.1](https://github.com/jrwesolo/yumsync/tree/v0.1.1) |

v0.1.2 (2016-01-21)
-------------------

Updates in the CentOS 7 image introduced a yum plugin called OVL. This
plugin was then being used when python was syncing repos. Tons of
"permission denied" errors were showing up in the logs. OVL now gets
disabled before Yumsync gets run.

### Bugfix

* Disable yum plugin `ovl` before `yumsync` runs

| Yumsync |
| :-----: |
| [v0.1.1](https://github.com/jrwesolo/yumsync/tree/v0.1.1) |

v0.1.1 (2016-01-21)
-------------------

### Bugfix

* Fixed incorrect use of `pass` in bash script (this isn't python!)

| Yumsync |
| :-----: |
| [v0.1.1](https://github.com/jrwesolo/yumsync/tree/v0.1.1) |

v0.1.0 (2016-01-20)
-------------------

This is the initial release of the Docker image of Yumsync.

| Yumsync |
| :-----: |
| [v0.1.1](https://github.com/jrwesolo/yumsync/tree/v0.1.1) |
