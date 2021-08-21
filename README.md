Role Name
=========
ansible-abrt-redhat

Description
---------------
Ansible role to disable the automatic bug reporting tool on Red Hat Linux systems.

This role was developed and tested on a Mint 20.2 system using [Molecule 3](https://molecule.readthedocs.io/en/latest/) with the Docker driver. A simple Dockerfile and registry info are included to use basic Red Hat 7 and 8 container images from [Red Hat's container registry](https://access.redhat.com/terms-based-registry/).

Full instructions for setting up this environment are a available at GeoffStratton.com.

To use actual RHEL images you'll need to generate a Red Hat Container Registry service account. (Yes, you can do with this with a free Red Hat Developer subscription.) You'll then need to provide your username and password token to the molecule.yml file; I just used shell variables but you could also use a CI/CD tool or other methods.

Requirements
--------------
* ansible
* molecule
* python

License
-------
Apache 2.0

Author Information
------------------
Geoff Stratton
