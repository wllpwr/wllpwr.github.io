---
layout: post
title:  "inconsistency and android"
---

Samsung, Google, OnePlus, LG, Sony, I could go on forever. The number of Android device distributors is a mile long. Unfortunately, this is contributing to one of Android’s longest-running problems: inconsistency.  Anyone who has followed the Android development scene for even a few months would likely know that this is a real problem.

# os updates and fragmentation
This is possibly the most outstanding issue when it comes to Android inconsistency. To push the newest devices, manufacturers will choose to abandon major Android updates after only a couple of years on the devices. 

### samsung
Samsung is arguably the most notorious when it comes to this. Their devices get around 2 years of major Android versions before they’re dropped. The Galaxy S8 that I bought in only 2017 is now left behind on Android 9. I have personal experience with their lackluster Android version support and can vouch for its fragmentation. 

Is two years really a satisfactory timespan for devices this expensive? Why are their flagship devices getting left behind? It’s clear that this is just done for marketing reasons, to push people to buy their latest devices.

### amazon
A lesser-known, but perhaps a more extreme example of companies failing to push major Android updates is Amazon. I was recently given an old Kindle Fire HDX 3rd gen, a tablet made in 2013. The specs aren’t impressive (besides that crisp 1080p screen). 

Consider that Android 4 was released in 2013. You would think that this tablet was upgraded to perhaps Android 6 or 7 as their final release. You would be wrong because this tablet has not gotten a single major Android upgrade. It will remain on Android 4 for the rest of its time. 

The Android community is fantastic, and there has been work to port LineageOS to the device. Currently, with rooting the Kindle, [this device can get up to Lineage 14.1, based on Android 7.1.2](https://forum.xda-developers.com/t/rom-05-jul-2020-lineageos-14-1.3517481/). There is more ongoing work to get these tablets running Lineage 16, based on Android 9. This, however, is not a feasible solution for less tech-savvy individuals. 

An argument can be made for Amazon that they have their own FireOS with their own App Store, which could be considered to be separated from the typical ecosystem.  But the fact of the matter is, these devices are still based on Android. I would imagine that there are several security vulnerabilities on Android 4 that are patched in Android 5 or 6.

### verizon
I can bet that most don’t expect to see this one on the list. Yes, Verizon is contributing to this fragmentation as well, although perhaps not as directly as device manufacturers themselves are. On devices resold through Verizon themselves, they lock the bootloader. Apparently, many years ago [they were actually brought to court for doing this](https://www.extremetech.com/computing/120771-what-is-a-bootloader-and-why-does-verizon-want-them-locked).

I have a Galaxy S4, S6, and S8, all with locked bootloaders. Without exploits discovered by the community, it is impossible to flash newer versions of Android onto these devices. For now, they are forever doomed to run whatever Samsung leaves these devices on. 

### what does this mean for users?
This problem would seem to mostly affect users more than developers. Consumers waste money on a flagship device that won’t support the latest versions of Android. iOS clearly has Android beat in this regard – even my iPhone 6S still supports iOS 14.  

### what does this mean for developers?
There is a lack of consistency when it comes to developing on Android. Because API levels widely vary within the ecosystem, it becomes difficult to support most of the market if you just want to target the latest versions. 

Thankfully, there has been work done by Google to bring these newer APIs to older devices. This has mostly mitigated the issues involved with many different API levels. Without these efforts, either older Android versions would be forced to rot, or manufacturers would actually have an incentive to continue updating their devices. 

### project treble
Google has created [Project Treble](https://android-developers.googleblog.com/2017/05/here-comes-treble-modular-base-for.html) to attempt to help manufacturers keep their devices on the latest versions. There needs to be wider adoption of this project, especially by Samsung, if we hope for this to succeed. 

# ui design 
This is perhaps a topic of Android that does not get as much attention. Everyone has their own vision for Android, and unfortunately, it sometimes does not match up with Google’s Material Design guidelines.

### samsung
As with many things Samsung is notorious for, inconsistency in their UI design is maybe at the top of that list. Throughout Android’s lifecycle, they have switched their design language, not once, but twice. From TouchWiz to Samsung Experience to One UI 1 and 2, Samsung continues jumping ship from one thing to another. These differences in UI design not only fragment the Material Design ecosystem, but it fragments the Samsung ecosystem as well. 

### google
Another example of an unexpected entry on this list. To a degree, Google contributes to the UI design fragmentation as well. For their Pixel phones, they opt to use grey colors for the background of their apps in dark mode. This is most prominent in their phone, calculator, and messages apps. One thing that doesn’t match up is that AOSP apps tend to keep their backgrounds a solid #000000 black. Even the Pixel’s own settings app uses this pure black, while the rest of the apps don’t. I have yet to figure out why this inconsistency exists. Their own apps don’t seem to conform to their Material Design standards.

### what does this mean for users?
Users downloading apps from the Play Store (especially on a Samsung device) will experience inconsistency in UI design. Samsung’s One UI heavily clashes with the current Material Design standards. Google's less-so, but I believe it's still an issue.

iOS again has the upper hand here – Apple is the only one making the devices. They can make one UI for all their devices, and it is consistent. 

### what does this mean for developers?
Clearly, this issue causes problems during the UI design steps. How is a developer supposed to make sure their app conforms to every popular design guideline in the ecosystem? Between AOSP, Samsung, and Google’s "Material Design 2", it’s impossible to create a consistent app. 

I’m not sure if something along these lines has been created already, but there should be some sort of library to on-the-fly adjust UI to match the device the app is on. There needs to be flexibility, so if an app’s design was created for AOSP, it can quickly convert that app to the One UI design standards. Closing the UI fragmentation gap will make the Android experience more pleasant for everyone involved.  
