# Stem-Deck-Drive-Clone
how to clone internal nvme drive to an external for upgrade

you will need a external nVME enclosuer that is a nVME m-key connector (not sata b-key.)
once the external drive is connected, go to deasktop mode and use the following command.

clone command: dd if=/dev/nvme0n1 of=/dev/sda oflag=sync bs=128M status=progress

*take no responsibility for the use of this command or loss of data.
