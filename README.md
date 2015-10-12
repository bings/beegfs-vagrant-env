# beegfs-vagrant-env
Vagrant environment for trying out BeeGFS, latest release 2015.3 (see [http://www.beegfs.com])

Makes virtual machines for mgmt server, metadata server, storage node and a client.
Uses ansible to install BeeGFS stuff.

    vagrant up
    vagrant status
    vagrant ssh client0
    ls -l /mnt/beegfs
