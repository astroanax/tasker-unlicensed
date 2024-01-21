# tasker-unlicensed
Patch to remove the license checking mechanism from [Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm)

DISCLAIMER - ONLY FOR eDuCaTiOnAl PURPOSES 🥰 !1!1!1

Working as of version 6.2.22
With this patch, you can use the Tasker app for free.

1. Download the apk from a trusted place such as APKMirror, or from the [developer's website](https://tasker.joaoapps.com/download.html) directly
2. Use [apktool](https://apktool.org) to disassemble the apk with `apktool d Tasker.X.Y.ZZ.apk` and `cd Tasker.X.Y.ZZ/`
3. Download the patch with `wget https://raw.githubusercontent.com/astroanax/tasker-unlicensed/master/smali.patch`
4. Apply the patch with `patch -p1 < smali.patch`
4. Run `apktool b`. The generated apk will be under Tasker.X.Y.ZZ/dist/
5. Install and profit???
