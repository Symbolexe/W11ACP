# W11ACP
⚠️ **In this README.md file, we will check how to activate Windows 11 and 10 for free.** ⚠️
# Requirements
1. Be sure to be connected to the Internet. ✔️
2. Make sure you have one of the versions of Windows listed below. ✔️
# Tested versions
### Windows 10
1. Windows 10 Home [✔️]
2. Windows 10 Pro [✔️]
3. Windows 10 Enterprise [✔️]
### Windows 11
1. Windows 11 Home [✔️]
2. Windows 11 Pro [✔️]
3. Windows 11 Enterprise [✔️]
# Necessary actions
You can do this operation after installing Windows and you don't need any **updates** or **special software**.
## First Step
open **CMD** as Administrator
![Screenshot (1)](https://github.com/Symbolexe/W11ACP/assets/140549630/a27dc27a-a2c2-4680-b75b-230183c50acb)
## Second Step
In order, one by one, **copy** these commands and **paste** them in the **cmd**.

`slmgr.vbs /upk`

`slmgr.vbs /cpky`

`slmgr.vbs /ckms`

`DISM /online /Get-TargetEditions`

👉 : If you see "Professional" in the list, then you can upgrade your Windows edition to Pro for free! ✔️

`sc config LicenseManager start= auto & net start LicenseManager`

`sc config wuauserv start= auto & net start wuauserv`

`changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T`

`slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX`

`slmgr /skms kms8.msguides.com`

`slmgr /ato`

## Final Step

After completing the above commands, you will see the *successful* message, which means that your Windows has been activated.

Now, Restart your windows and enjoy 😊 
