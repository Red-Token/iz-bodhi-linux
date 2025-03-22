# iz-bodhi-linux

### Debian Trixie

Install testing netiso

https://cdimage.debian.org/cdimage/weekly-builds/amd64/iso-cd/debian-testing-amd64-netinst.iso

#### Create Debain ISO

    sudo dd if=debian-testing-amd64-netinst.iso  of=/dev/sda bs=4M status=progress && sync
