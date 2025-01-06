# 2.1 Install Generic Server or PC

## 2.1.1 Prepare Installation Media

We can download proxmox-port iso from [APQA](https://mirrors.apqa.cn/proxmox/isos/) or [Lierfang](https://mirrors.lierfang.com/proxmox/isos/).

## 2.1.2 Instructions for GNU/Linux or Unix

If you usb flash drive is /dev/sdc

```
# dd bs=1M  if=./proxmox-ve_*.iso of=/dev/sdc
# sync
```

## 2.1.3 Instructions for Windows

### Using Etcher 
Etcher works out of the box. Download Etcher from https://etcher.io. It will guide you through the process of selecting the ISO and your USB flash drive.

### Using Rufus 
Rufus is a more lightweight alternative, but you need to use the DD mode to make it work. Download Rufus from https://rufus.ie/. Either install it or use the portable version. Select the destination drive and the Proxmox VE ISO file.


## 2.1.4 Using the Proxmox VE Installer
