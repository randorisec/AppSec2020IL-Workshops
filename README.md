# OWASP Virtual AppSec Israel 2020

During the OWASP AppSec Israel 2020 event, RandoriSec delivered 2 workshops:

* [Android Mobile Hacking Workshop](https://appsecil2020.sched.com/event/fBun/android-mobile-hacking-workshop?iframe=no)
* [iOS Mobile Hacking Workshop](https://appsecil2020.sched.com/event/fBuq/ios-mobile-hacking-workshop?iframe=no)

This repository contains the materials used during the workshops.


If you want to try those workshops, you need to use a Virtual Machine (or a physical one!) containing the following tools: 

* Android Studio
* apktool
* JADX
* Ghidra
* Objection
* Frida

Another alternative is to use Mobexler. We recommend to apply the following steps in order to use it:

* Install VMWare Player 15 (**DO NOT USE VirtualBox!!**)
https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html

* Download **Mobexler** virtual machine (default password: 12345)
https://mobexler.com/download.htm

* Import the OVA file using VMWare Player 15. If an error message appears sayng the OVA file didn't pass the OVF specifications, please click retry. It should work :)

	
* Inside the Virtual Machine, you need to enable kvm permission to create an emulator
https://stackoverflow.com/questions/37300811/android-studio-dev-kvm-device-permission-denied

   1. sudo apt install qemu-kvm
   2. sudo adduser mobexler kvm
   3. reboot
