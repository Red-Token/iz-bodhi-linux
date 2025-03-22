# iz-bodhi-linux

### Debian Trixie

Install testing netiso

https://cdimage.debian.org/cdimage/weekly-builds/amd64/iso-cd/debian-testing-amd64-netinst.iso

#### Create Debain ISO

    sudo dd if=debian-testing-amd64-netinst.iso  of=/dev/sda bs=4M status=progress && sync

#### Install thunar

    apt install thunar

#### Install git

    apt install git

#### Install sudo

    apt install sudo

#### Clone the patch

    git clone https://github.com/BodhiDev/Distros

#### Run the script

    cd Distros/Debian/
    sudo
    ./trixie.install.sh
