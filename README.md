# Kolla Snap

This repository contains the source code of the snap for the OpenStack Kolla

## Installing this snap

Build with `snapcraft` and install with `snap`

    snapcraft
    sudo snap install zioproto-kolla_3.0.2_amd64.snap --dangerous --classic
    ls -1 /snap/bin/zioproto-kolla.* | cut -f 2 -d . | xargs sudo snap alias zioproto-kolla

In the future the kolla snap can be installed directly from the snap store:

    sudo snap install --beta --classic zioproto-kolla

## Support

Please report any bugs related to this snap on
[Launchpad](https://bugs.launchpad.net/snap-kolla/+filebug).

Alternatively you can find the OpenStack Snap team in `#openstack-snaps`
on Freenode IRC.
