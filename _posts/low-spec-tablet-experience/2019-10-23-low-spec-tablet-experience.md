---
layout: post
title:  "the low-spec tablet experience"
---

My ASUS Transformer T100TAF has some terrible specs: an Intel Z3735 clocking at around 1.50 GHz, just **2 GB** of onboard memory, and 32 GB of eMMC storage. While it’s a 64-bit processor, the bootloader is limited to just 32-bit, because of some weird things manufacturers did with early Bay Trail processors. All in all, this thing is… well.. *not good*.

<img align="center" width="50%" height="50%" src="/assets/img/low-spec-tablet-experience/nokeyboard.jpg" vspace="25">

The appeal to this device, however, is that it’s a detachable tablet. It pops right off the keyboard with a press of a button. The Windows tablet experience is very nice, with complete touch gesture support, and full system navigation is possible with touch alone.

The only problem here is that Windows 10 is horrible when it comes to resource management. At cold boot, I was looking at at least a gigabyte and half of memory used, as well as choppiness during something as simple as web browsing. The CPU couldn’t even run at it’s full capabilities because I was limited to 32-bit versions of Windows. Overall, the experience was pretty bad, so I did what I usually do: switch to Linux.

If you’ve been keeping up with the Ubuntu world within the past few years, you may know that [Ubuntu has dropped support for 32-bit isos](https://itsfoss.com/ubuntu-drops-32-bit-desktop/). So, I had to download version 16.04.6, and then upgrade up to 19.04. Several hours later, and I had a working Ubuntu tablet.
“Working” however, is the only compliment I could give to the experience. Ubuntu’s GNOME desktop has very lackluster touch support, and a barely functional touch keyboard. KDE was very much the same. I really had hoped that Ubuntu may have been the solution for this thing, but until better touch support comes out for the distros, I’m out of luck.

<img align="center" width="50%" height="50%" src="/assets/img/low-spec-tablet-experience/android.jpg" vspace="25">

So, I thought, what’s the next best operating system with touch support? I then turned to [Android x86](https://www.android-x86.org/). It’s got the apps I want, and the touch support I need. After some searching, I went with [PrimeOS](https://www.primeos.in), as it has a more familiar taskbar and multitasking setup compared to stock. It works well, with a few minor issues, and one big one. It has a 32-bit build, which worked fine.

To start, Bluetooth doesn’t work at all. Not an issue, since I don’t really need it.Wi-Fi is a little spotty on boot, but works fine otherwise. In addition, sound doesn’t work. This isn’t a *huge* issue, but it’s a little disappointing when I want to watch a video or so. The biggest, most crippling flaw, is that there is no support for sleep states. No sleep states means the only thing I can do when I want to put the tablet down and come back later is to fully turn it off. I’m hoping the PrimeOS developers add proper support for sleep states on this device in the future.
