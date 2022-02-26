# Automatic Build Repository for MiniSCT-Linux

[![CI](https://github.com/Semi-ATE/MiniSCT-Linux/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/MiniSCT-Linux/actions/workflows/CI.yaml)
[![CD](https://github.com/Semi-ATE/MiniSCT-Linux/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/MiniSCT-Linux/actions/workflows/CD.yaml)

The build uses the following repositories :

| Repository | Continuous Integration | Continuous Delivery |
|:------ |:----------------------:|:-------------------:|
| [SCT8-ARTIX](https://github.com/Semi-ATE/SCT8-ARTIX) | [![CI](https://github.com/Semi-ATE/SCT8-ARTIX/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-ARTIX/actions/workflows/CI.yaml) | [![CD](https://github.com/Semi-ATE/SCT8-ARTIX/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-ARTIX/actions/workflows/CD.yaml) |
| [SCT8-KINTEX](https://github.com/Semi-ATE/SCT8-KINTEX) | [![CI](https://github.com/Semi-ATE/SCT8-KINTEX/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-KINTEX/actions/workflows/CI.yaml) | [![CD](https://github.com/Semi-ATE/SCT8-KINTEX/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-KINTEX/actions/workflows/CD.yaml) |
| [SCT8-ZYNQ](https://github.com/Semi-ATE/SCT8-ZYNQ) | [![CI](https://github.com/Semi-ATE/SCT8-ZYNQ/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-ZYNQ/actions/workflows/CI.yaml) | [![CD](https://github.com/Semi-ATE/SCT8-ZYNQ/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-ZYNQ/actions/workflows/CD.yaml) |
| [BootLoader-MK20DN512](https://github.com/Semi-ATE/BootLoader-MK20DN512) | [![CI](https://github.com/Semi-ATE/BootLoader-MK22FX512/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/BootLoader-MK22FX512/actions/workflows/CI.yaml) | [![CD](https://github.com/Semi-ATE/BootLoader-MK22FX512/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/BootLoader-MK22FX512/actions/workflows/CD.yaml) |
| [BootLoader-MK22FN1M0](https://github.com/Semi-ATE/BootLoader-MK22FN1M0)  | [![CI](https://github.com/Semi-ATE/BootLoader-MK22FN1M0/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/BootLoader-MK22FN1M0/actions/workflows/CI.yaml) | [![CD](https://github.com/Semi-ATE/BootLoader-MK22FN1M0/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/BootLoader-MK22FN1M0/actions/workflows/CD.yaml) |
| [BootLoader-MK22FX512](https://github.com/Semi-ATE/BootLoader-MK22FX512) | [![CI](https://github.com/Semi-ATE/BootLoader-MK22FX512/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/BootLoader-MK22FX512/actions/workflows/CI.yaml)| [![CD](https://github.com/Semi-ATE/BootLoader-MK22FX512/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/BootLoader-MK22FX512/actions/workflows/CD.yaml) |
| [SCT8-MCU-MK20DN512](https://github.com/Semi-ATE/SCT8-MCU-MK20DN512) | [![CI](https://github.com/Semi-ATE/SCT8-MCU-MK20DN512/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-MCU-MK20DN512/actions/workflows/CI.yaml) | [![CD](https://github.com/Semi-ATE/SCT8-MCU-MK20DN512/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-MCU-MK20DN512/actions/workflows/CD.yaml) |
| [SCT8-MCU-MK22FX512](https://github.com/Semi-ATE/SCT8-MCU-MK22FX512) | [![CI](https://github.com/Semi-ATE/SCT8-MCU-MK22FX512/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-MCU-MK22FX512/actions/workflows/CI.yaml) | [![CD](https://github.com/Semi-ATE/SCT8-MCU-MK22FX512/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/SCT8-MCU-MK22FX512/actions/workflows/CD.yaml) |
| [MiniPower-MCU-MK22FN1M0](https://github.com/Semi-ATE/MiniPower-MCU-MK22FN1M0) | [![CI](https://github.com/Semi-ATE/MiniPower-MCU-MK22FN1M0/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/MiniPower-MCU-MK22FN1M0/actions/workflows/CI.yaml) |[![CD](https://github.com/Semi-ATE/MiniPower-MCU-MK22FN1M0/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/MiniPower-MCU-MK22FN1M0/actions/workflows/CD.yaml) |
| [MiniPower-MCU-MK22FX512](https://github.com/Semi-ATE/MiniPower-MCU-MK22FX512) | [![CI](https://github.com/Semi-ATE/MiniPower-MCU-MK22FX512/actions/workflows/CI.yaml/badge.svg)](https://github.com/Semi-ATE/MiniPower-MCU-MK22FX512/actions/workflows/CI.yaml) |[![CD](https://github.com/Semi-ATE/MiniPower-MCU-MK22FX512/actions/workflows/CD.yaml/badge.svg)](https://github.com/Semi-ATE/MiniPower-MCU-MK22FX512/actions/workflows/CD.yaml) |

# Installation of MiniSCT-Linux on SD card

1. On a Linux machine, insert the SD card, and open [gparted](https://gparted.org/) (as root)

![image](https://user-images.githubusercontent.com/3516972/155651569-05d6707d-500a-440c-864d-c181edce0f1b.png)

2. Unmount the SD card (right click on the partition and chose `Unmount`)

3. Delete the old partition (right click on the partition and chose `Delete`)

![image](https://user-images.githubusercontent.com/3516972/155653672-bc184621-56a8-40bd-a3fa-cd9f3fd7ba98.png)

4. Create a primary partition of 1GB in `fat32` with the label `BOOT` (right click on the partition and chose `New`)

![image](https://user-images.githubusercontent.com/3516972/155650278-757214b1-c781-4c5f-a561-e83d420c468e.png)

4. Create another primary partition with as size the remaining free space in `ext4` with the label `ROOT` (right click on the partition and chose `New`)

![image](https://user-images.githubusercontent.com/3516972/155650482-342f9c1f-336e-40cd-ad4c-b61866be9e6c.png)

5. Apply the changes (hit the green check mark and hit `Apply` and then `Close`)

![image](https://user-images.githubusercontent.com/3516972/155650658-8a9e28ea-2a75-4a9d-89f8-144f756e5577.png)
![image](https://user-images.githubusercontent.com/3516972/155650719-b1a19fa9-1c9e-4cae-a8b0-81e50381274b.png)
![image](https://user-images.githubusercontent.com/3516972/155650758-dc36b2eb-a16b-44ca-a7e0-ccfcc1957370.png)
![image](https://user-images.githubusercontent.com/3516972/155650799-afbc7eb5-28d0-45f2-a429-fb1c956fa72d.png)

5. Enable the `boot` flag of the `fat32` partition (right click on the `fat32` partition and chose `Manage Flags`, then enable the boot flag and `close` the window)

![image](https://user-images.githubusercontent.com/3516972/155650982-b16f2b9a-b44f-4e93-9dfd-247e57194966.png)
![image](https://user-images.githubusercontent.com/3516972/155651073-b81238b6-1c1e-466f-be3f-3c845e256cf2.png)

6. Close out `gparted`

7. Take out the SD card (it is already unmounted)

8. Go to the [MiniSCT-Linux](https://github.com/Semi-ATE/MiniSCT-Linux) repo. 

![image](https://user-images.githubusercontent.com/3516972/155654751-83adb1c0-521d-4de0-8580-a9d7875ed98a.png)

9. Go to the lates release 

![image](https://user-images.githubusercontent.com/3516972/155655127-916b1b3c-3246-428a-867e-0c85d8c0812c.png)
![image](https://user-images.githubusercontent.com/3516972/155655155-79d45ea6-716d-46a5-be93-f525e5bb9aba.png)

10. Download the following files : 

  - BOOT.BIN
  - boot.scr
  - image.ub
  - ubuntu-mpsoc-arm64.tar.xz

Notes: 
  - The other files are not needed for this procedure
  - The download of the last file will take a while as it is BIG.

11. Insert the SD card again (it should auto-mount)

12. Open a terminal and 'copy' the files in place like this :

```bash
(maxiconda) me@mybox:~$ cd /media/me
(maxiconda) me@mybox:/media/me$ ls
BOOT  ROOT
(maxiconda) me@mybox:/media/me$ cd BOOT
(maxiconda) me@mybox:/media/me/BOOT$ cp ~/Downloads/BOOT.BIN .
(maxiconda) me@mybox:/media/me/BOOT$ cp ~/Downloads/boot.scr .
(maxiconda) me@mybox:/media/me/BOOT$ cp ~/Downloads/image.ub .
(maxiconda) me@mybox:/media/me/BOOT$ ls
BOOT.BIN  boot.scr  image.ub
(maxiconda) me@mybox:/media/me/BOOT$ cd ../ROOT
(maxiconda) me@mybox:/media/me/ROOT$ sudo tar -xf ~/Downloads/ubuntu-mpsoc-arm64.tar.xz 
[sudo] password for me:
(maxiconda) me@mybox:/media/me/ROOT$ ls
bin  dev  etc  home  lib  lost+found  media  mnt  opt  proc  root  run  sbin  snap  srv  sys  tmp  usr  var
(maxiconda) me@mybox:/media/me/ROOT$ cd
(maxiconda) me@mybox:~$ umount /media/me/BOOT
(maxiconda) me@mybox:~$ umount /media/me/ROOT
(maxiconda) me@mybox:~$ ls /media/me/
(maxiconda) me@mybox:~$ 
```

Note: Ofcourse replace `me` with your own login 😉

13. Remove the SD-Card, and insert it in the MiniSCT, plug in a network cable, a power cable and a serial cable as per the below picture 

![image](https://user-images.githubusercontent.com/3516972/155658587-62e9add9-f968-4ada-9417-0156cb687e81.png)

14. Open a serial terminal with 11520 8N1 (`sudo minicom` ?)

15. Turn on the MiniSCT and wait until the system is booted up (monitor your serial terminal)

16. Log in as root (password is `root`)

![image](https://user-images.githubusercontent.com/3516972/155659843-5157e22d-c54c-4a26-bc9f-a38fc7f4d4a5.png)

17. Run the `postinstall` script

```bash
...
[   33.918653] cloud-init[575]: 2022-02-25 05:31:32,773 - cc_final_message.py[WARNING]: Used fallback datasource

Ubuntu 20.04.3 LTS sct8 ttyPS0

sct8 login: root
Password: 
Welcome to Ubuntu 20.04.3 LTS (GNU/Linux 5.4.0-xilinx-v2020.1 aarch64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

  System information as of Fri Feb 25 05:32:38 UTC 2022

  System load:  0.71              Processes:             89
  Usage of /:   5.7% of 28.15GB   Users logged in:       0
  Memory usage: 3%                IPv4 address for eth0: 192.168.2.118
  Swap usage:   0%

 * Super-optimized for small spaces - read how we shrank the memory
   footprint of MicroK8s to make it the smallest full K8s around.

   https://ubuntu.com/blog/microk8s-memory-optimisation

128 updates can be applied immediately.
80 of these updates are standard security updates.
To see these additional updates run: apt list --upgradable


Last login: Fri Feb 25 05:30:40 UTC 2022 on ttyPS0
root@sct8:~# postinstall 
...
```

Notes:
  - This script will take a while to finish but it **NEEDS TO BE RUN** in order to get a correctly installed system!
  - The MiniSCT needs the network cable to access the internet !
  - Once the `postinstall` script did run, it will remove itself!

18. Reboot to finalize the postinstall



