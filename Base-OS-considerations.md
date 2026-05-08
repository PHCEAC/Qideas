
# Requirements considered in selection of base OS for Dom0

* similar considerations are relevant to Whonisx/KS/etc

## Base choices

Necessary services for Q :

* vm management
* vchan or similar for Q-rpc
* xen- like memory share for fb-like graphics isolation
* handle PT for hw compartmentalisation

Not sure reqs

* access to/mgmnt of  disks? or blockdevs?
  * StorageVM?
  * can disk ctrlrs be PT?
  * minimal partn/block if?

Reasonable and practical reqs

* Wide hw compat, esp recent hw
* packagages?
* Updatable
* Installable *sigs, etc.
* Posixy tools?
* power mgmnt?

Initial choice:

* Linux distro
* Microkrnel - MirageOS? 
* Linux/kvm (no xen)

https://www.whonix.org/wiki/Dev/Operating_System
