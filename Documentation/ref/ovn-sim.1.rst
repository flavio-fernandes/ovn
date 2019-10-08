=======
ovn-sim
=======

Synopsis
========

``ovn-sim`` [*option*]... [*script*]...

Description
===========

``ovn-sim`` is a wrapper scripts that adds a few ovn related commands on
top of ``ovs-sim``.

``ovs-sim`` provides a convenient environment for running one or more Open
vSwitch instances and related software in a sandboxed simulation environment.

To use ``ovn-sim``, first build Open vSwitch, then invoke it directly from the
build directory, e.g.::

    git clone https://github.com/openvswitch/ovs.git
    cd ovs
    ./boot.sh && ./configure && make
    cd ..
    git clone https://github.com/ovn-org/ovn.git
    cd ovn
    ./boot.sh && ./configure --with-ovs-source=${PWD}/../ovs
    make
    utilities/ovn-sim

TO BE CONTINUED......

