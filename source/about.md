# 1. About Proxmox Port

Proxmox Port is a project that ports Proxmox VE and Proxmox Backup Server to non-amd64 platforms. At present, the complete porting to loongarch64 and arm64 has been completed, and the support for riscv64 has also been added to the code. However, packages for riscv64 have not been built yet.

Code licensed under the  AGPLv3 (GNU Affero General Public License version 3).

## 1.1 Which devices are supported?

Theoretically, devices with arm64 chips and those with loongarch64 are both supported. We will have a support list and put it in this document for your reference.

## 1.2 What are the differences from the official version?

- We have provided code that supports multiple architectures. Meanwhile, we have also offered some optimization treatments for QEMU to make it more user-friendly.

- We maintain our own set of kernels for users' specific hardware, such as LoongArch and Phytium.

- The code can also run on amd64, making the compatibility of hybrid clusters stronger.

## 1.3 Support

Proxmox Port is a downstream project. All support should be provided by us. Proxmox will not be responsible for this code. This is something that everyone needs to know. Please don't go to the forum to seek support.

Currently, we offer both community support and commercial support. For community support, discussions can be held on GitHub or in our community communication groups.

 - Community support
    - github: https://github.com/jiangcuo/Proxmox-Port
    - discord: https://discord.com/channels/1040085308223520819/1089221423148568627
    - Tencent QQ: 750937440

 - Community support
    - mailto: service@lierfang.com
