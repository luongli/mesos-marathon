# Playa Mesos Configuration

### config.json
The following options must be set in `config.json`:

###### _*platform*_
Virtualization platform (possible choices are: `virtualbox`, `vmware_fusion`, `vmware_workstation`)

###### _*box_name*_
Vagrant box-name

###### _*base_url*_
Base URL where the Vagrant box images are stored.
Download path is dynamically extracted with this schema: `base_url`/`platform`/`box_name`.box

###### _*ip_address*_
IP address used by the VM on a private network using a /24 netmask

###### _*vm_ram*_
MB of RAM allocated to the VM

###### _*vm_cpus*_
Number of CPU cores allocated to the VM
