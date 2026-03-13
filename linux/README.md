<h1 align="center">
    <img src="../assets/virtual-machine.png" alt="virtual-machine"><br>
    <img src="https://github.com/JaKooLit/Telegram-Animated-Emojis/blob/main/Activity/Sparkles.webp" alt="Sparkles" width="45" />
    LINUX
    <img src="https://github.com/JaKooLit/Telegram-Animated-Emojis/blob/main/Activity/Sparkles.webp" alt="Sparkles" width="45" />
</h1>

This first project mainly involves setting up a virtual machine running `Debian` (*Debian 13* in this case) and testing to make sure everything is working properly.

## 📥️ Installation

> [!NOTE]
> Operating systems are usually installed with a "disk image" that can be written to a USB stick or CD/DVD for installation on a computer, or kept as is for installation in a virtual machine (which is the case here).

Install Debian (ISO installer "netinst" is recommended) in a VM (Virtual Machine). The steps are :

- Create the VM.
- Start the VM and attach the ISO file as an optical drive (CD/DVD).
- Follow the steps of the installer, it will reboot with a Debian system ready to use.

## 🔍️ Audit

The auditor has to check if :

- the virtualization software is correctly installed on the auditee's machine ;
- the virtual machine boot Debian properly (**in less than 2 minutes**) ;
- the auditee can log in and shut down the VM using a command line from the console.

> [!IMPORTANT]
> Use the following command 👇🏿 to shut down the VM :

```bash
sudo poweroff
```
