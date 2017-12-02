# needs-reboot
RHEL/CentOS/Oracle Linux python script to check if reboot is recommended since last package installation/update.
Packages where a reboot is recommended are taken from https://access.redhat.com/solutions/27943.

## Requirements
yum-utils should be installed to resolve python dependencies.

## How to use
Place the script at e.g. /usr/bin and make it executable
