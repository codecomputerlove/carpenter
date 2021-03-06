# Change Log - Ubuntu 16.04

#### v0.2.1 (8th August 2017)

  - Package upgrades as of 2017-08-08
  - Fix security upgrades at first boot potentially causing apt locks. Now blocks SSH access until completed
  - Fix warnings from apt operations due to old files in conf dir

#### v0.2.0 (25th July 2017)

Features: 

  - Package upgrades as of 2017-07-25
  - Install security updates on first-boot
  - Automated security updates
  - Increase disk size to 120GB (Was 40GB)

#### v0.1.0 (16th May 2015)

Features:

  - Package upgrades as of 2017-05-16
  - Generalized before first-use. Includes clearing logs, DHCP leases, hostname reset, and history removal.
  - ufw enabled with ssh rate limited to match production environment

#### v0.0.2 (12th May 2015)

Bug Fixes:

 - Incorrect ownership of vagrant user's ssh configuration, causing Vagrant to fail during the "replace insecure keys" step

#### v0.0.1 (5th May 2017)

Features:

 - Package upgrades as of 2017-05-03
 - Initial release
