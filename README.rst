Manila image elements project
==============================

This repo is a place for Manila-related for diskimage-builder elements.

* Free software: Apache license
* Source: http://git.openstack.org/cgit/manila-image-elements
* Bugs: http://bugs.launchpad.net/manila-image
* Built Images: http://tarballs.openstack.org/manila-image-elements/images


Build instructions
------------------

Script for creating Ubuntu based image with our elements and default parameters. You should only need to run this command:

.. sourcecode:: bash

    tox -e buildimage
