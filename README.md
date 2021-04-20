# R9-nano-Sweet-Bios

ENG version
-----
**Sweet Point vBios for AMD Readon R9 nano**


These Bios files is already tested on my R9 nano for over half years, and I have tried my best to figure out the "sweet point" for R9 nano. 

I will mark their main performance index and the fan speed under different GPU temp so that you can decide which one you'd like to use.

Almost all the vBios use lower GPU voltage to reduce the power consumption and thermal stress. I'll upload two groups vBios, one is for best performance and higest frequency and another one have lower frequency for ITX case to work stable.

All of the vBios files are for HIS R9 nano and please check your hardware ID which is shown in GPU-Z first to aviod your graphics card dead.

And if you unfortunately "bricked" your card, try to find a small switch on the top of your card. Most of (almost all) R9 nano is designed as Dual-Bios so you can switch you bios from broken one to the normal one, after you booted into OS you can hot switch vBios back and reflash the vBios.

All of the vBios is added support of UEFI boot up and the UEFI support code is from ASUS R9 nano vBios from https://www.techpowerup.com/vgabios/. 

You need a tool to flash the edited vBios file into your card, here we will use ATIflash Tool because the pretty and sexy GUI could make operation not so boring. And you can download this tool from here https://www.techpowerup.com/download/ati-atiflash/. 

I'm strongly recommend you that unzip ATIflash Tool in your C: disk and run it under administrator privilege, which will help you out of many trouble.




CHS version
-----

**AMD R9 Nano的最佳功耗点vBios**


我会在vBios文件上列出主要的性能指标和在不同温度下的风扇速度，这样你可以决定自己使用哪一个。

这些列出的vBios文件我已经在自己的R9 nano上测试了超过六个月，并且我一直在尝试找到最佳的平衡点。

几乎所有的vBios文件都下调了核心电压来降低功耗和改善发热。在这里的vBios有两组，第一组是标准频率或高频率用于高性能场景，另一组是降频散热改良vBios适用于ITX机箱稳定工作。

所有的vBios文件都是基于HIS（希仕）的R9 nano显卡，在你自己刷入之前请在GPU-Z上确定你的设备ID，以免显卡变砖。

如果你这个大聪明还是把自己的卡搞死了，你可以在你的显卡顶部找到一个小的黑色开关。几乎所有的R9 nano都是双Bios设计，简直是给折腾党量身定做的功能，你可以用开关切换到另一个vBios然后开机，这样就可以正常的进入系统，在你进入系统后可以用开关热切换vBios重新刷写。

所有的vBios都已经添加了UEFI启动支持，你可以高清的看到丑得一批的开机界面了(当然这不是主要目的XD)。UEFI支持的相关代码是从ASUS的R9 nano vBios中提取的，https://www.techpowerup.com/vgabios/ 侵删。

你需要一个写入工具来帮你刷写显卡vBios，在这里建议使用ATIflash Tool，GUI和汉化可以帮助你快速了解你要干什么。你可以在这里下载该软件 https://www.techpowerup.com/download/ati-atiflash/

强烈建议你把这个软件放在C盘根目录下并且用管理员模式运行，有任何问题请先考虑是不是这一步出错。

