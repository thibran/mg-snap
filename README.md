# mg Snap Package

[![Snap Status](https://build.snapcraft.io/badge/thibran/mg-snap.svg)](https://build.snapcraft.io/user/thibran/mg-snap)

[mg repo](https://github.com/hboetes/mg)

The snap should be build on an Ubuntu 16.04 host.
If the host is not available, install with:

    sudo snap install --beta core16

The `--beta` switch is needed because there is currently no stable release of `core16`.

## Build Steps

Install Snapcraft:

    sudo snap install --classic snapcraft

Then run inside the `mg-snap` folder:

    snapcraft

To install the snap-package from the local build:

    sudo snap install mg-thibran_*.snap --dangerous

The `--dangerous` is necessary because the local build snap is not signed by the snap-store.

### Alias (optional)

It's possible to create an alias with:

    sudo snap alias mg-thibran.mg mg

Note: Starting a snap for the first time is takes a bit longer than succeeding launches.

## Links

[Snapcraft Docs](https://docs.snapcraft.io/)  
[Snap Build Service](https://build.snapcraft.io/)  
[About Snaps](https://www.ubuntu.com/desktop/snappy)
