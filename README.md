# ZeroMQ Distributed Messaging (REDHAWK Shared Library)

This is a REDHAWK Shared Library (a.k.a., softpkg dependency) for the ZeroMQ Distributed Messaging library.

## Installation

You should install this in your REDHAWK Domain's SDRROOT with any other Components that will rely upon it for deployment.  On the Domain system:

    cd zmq
    ./build.sh
    cd cpp
    make install

> Note: You may still need to install language bindings.
