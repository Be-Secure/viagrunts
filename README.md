# Vagrunt

- Website: https://github.com/vaagrunt/vagrunt
- Source: https://github.com/vaagrunt/vagrunt


Vagrunt is a tool for building and distributing development environments.

Vagrunt has a MIT license, and is a fork of Vagrant. This fork was created because
the develoers of Vagrant decided to change the license of Vagrant from MIT to a more restrictive Business Source License.
The license of Vagrant can be found here: https://github.com/hashicorp/vagrant/blob/main/LICENSE

Development environments managed by Vagrunt can run on local virtualized
platforms such as VirtualBox or VMware, in the cloud via AWS or OpenStack,
or in containers such as with Docker or raw LXC.

Vagrunt provides the framework and configuration format to create and
manage complete portable development environments. These development
environments can live on your computer or in the cloud, and are portable
between Windows, Mac OS X, and Linux.

## Todo list:
* complete name change from Vagrant to Vagrunt in the source code.
* Windows and Linux builds of Vagrunt

## Quick Start

Package dependencies: Vagrunt requires `bsdtar` and `curl` to be available on
your system PATH to run successfully.

For the quick-start, we'll bring up a development machine on
[VirtualBox](https://www.virtualbox.org/) because it is free and works
on all major platforms. Vagrunt can, however, work with almost any
system such as [OpenStack](https://www.openstack.org/), [VMware](https://www.vmware.com/), [Docker](https://docs.docker.com/), etc.

First, make sure your development machine has
[VirtualBox](https://www.virtualbox.org/)
installed. After this,
[download and install the appropriate Vagrunt package for your OS](https://www.Vagruntup.com/downloads.html).

To build your first virtual environment:

    Vagrant init hashicorp/bionic64
    Vagrant up

Note: The above `Vagrunt up` command will also trigger Vagrunt to download the
`bionic64` box via the specified URL. Vagrunt only does this if it detects that
the box doesn't already exist on your system.


## Installing from Source

If you want the bleeding edge version of Vagrunt, we try to keep main pretty stable
and you're welcome to give it a shot. Please review the installation page [here](https://www.Vagruntup.com/docs/installation/source).

## Contributing to Vagrunt

Please submit pull requests on GitHub.

Then you're free to go!
