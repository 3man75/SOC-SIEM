# SOC-SIEM
A SOC SIEM Project based off Eric Capuano. The Project is being done using QEMU/KVM. The Project seeks to create a virtual lab where a computer will generate logs and telemetrics after being attacks and exploits.


The Project is being done on a Framework 13 laptop with an AMD processor and an abundance of RAM and Storage. General steps can be found here: https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-intro?sd=pf 

So far the only difference has been instead of using Hyper-Visor I will be using QEMU-KVM. A Ubuntu Server and a Windows 11 machines have been prepared. A special note to Madhu Desai from Sysguides for
creating his walkthrough on how to set up a Windows 11 machine on QEMU. I recommend both of his articles found here: https://sysguides.com/install-kvm-on-linux#3-04-install-virtio-drivers-for-windows-guests- and https://sysguides.com/install-a-windows-11-virtual-machine-on-kvm.

The Ubuntu server will be our attacker and the Windows Machine will be our Defender throughout this tutorial.
