# A9 Activation Guide
## (The solution for 64-bit A9 Devices having activation errors (issues uploading activation files to mnt2) on iOS 9.2-9.3.3)
An easy to follow guide which achieves official activation status and an untethered jailbreak (kokeshi9 untethered)
You will need to restore 1 or 2 times, so make sure you backup your data to cloud or storage before trying this.
If you are already on iOS 10+, just jailbreak it so that you can obtain the 4 activation tickets, else you will need to use iTunes or turdus_merula if you want to restore to iOS 10 and later so that you can obtain the tickets and restore back to 9.2-9.3.3.

## Benefits (why you should try this method)
- App Store works (by installing iTunesStoreFix in Ca1 repo)
- Gives you the real iOS 9 experience on your A9 devices
- Allows a full untethered jailbreak
- Setup.app will not be bypassed and you will be able to complete it as if the device is activated
- SIM Card works with data and signal

## Prerequisites
- An A9 device: iPhone SE, iPhone 6s/6s Plus, iPad 5th Generation
- A computer running macOS or Linux; Most AMD CPUs will not work due to its USB interfaces not supporting gaster/other pwning methods; Windows also will not work as we need to use many tools
- iOS 9.2-9.3.3 IPSW File
- turdus_merula
- Legacy iOS Kit; to temporarily move setup.app and Install Bootstrap (installs Cydia and required jailbreak files that can be reactivated with jbme.ddw.nu)
- A stable internet connection
- [4 Activation Tickets from iOS 10+](https://www.reddit.com/r/LegacyJailbreak/wiki/guides/a9ios9activation/#wiki_saving_activation_tickets)
- 1 Hacktivation Key in MobileGestalt.plist: [iPh0ne4s](https://www.reddit.com/r/setupapp/comments/1jviq3i/guide_manually_jailbreaking_ios_92933_unactivated/)
- Mac with AirDrop; iOS 9 is super restrictive while it is deactivated, therefore we will need to use AirDrop to send/receive the activation files to/from Filza

## Steps
### still work in progress**

### Part I: Restoring to iOS 10.3.3 to obtain necessary activation tickets
Note: if you are already on iOS 10 and above, you can skip to 8.
1. Download the latest release of turdus_merula from https://sep.lol/
2. Follow ios.cfw.guide to restore your A9 device to iOS 10.3.3
3. Jailbreak the device with Totally Not Spyware
4. Open Cydia and search for Filza File Manager, install it
5. Open Filza
6. Go into the 4 directories and use AirDrop to send the files to your Mac
- 

## Frequently asked questions
### Why is iOS 9.2-9.3.3 only supported?
This is because iOS 9 in deactivated state does not allow us to sideload apps or even install apps from websites like jailbreaks.app. Hence, we will need to use jbme.ddw.nu which only supports iOS 9.2-9.3.3 as a temporary jailbreak to place the activation files, set permissions and user access.

### Why do I need to restore to iOS 10.3.3+ first to obtain activation tickets?
Only iOS 10+ can be officially activated. Once you have jailbroken and have the 4 tickets uploaded and saved in a folder, you can keep it for older iOS activation. I have also tested iOS 10.3.3 activation tickets and they work well on iOS 9.
