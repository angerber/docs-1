---
layout: article
title: Install Steam
description: >
   Want to game on your super awesome new System76 machine?  Take a look at these instructions to install Steam, a marketplace for hundreds of Linux games.
keywords:
  - gaming
  - support
  - steam
image: http://support.system76.com/images/system76.png
hidden: false
section: pop-ubuntu

---

### Install Steam From the Pop!_Shop

Open the <u>Pop!_Shop</u> application. There, you can either search for Steam or click the <u>Steam</u> icon on the Pop!_Shop home page. 

![Pop!_Shop](/images/steam/pop_shop1.png)

Then, click the **install button**.

![Pop!_Shop](/images/steam/pop_shop2.png)

### Install Steam From Command Line

Press the Super Key <kbd><span class="fl-pop-key"></span></kbd><kbd>, <i class="fl-ubuntu"></i></kbd> and search for <u>Terminal</u>. Then, open the <u>Terminal</u> application.

![Activities Overview](/images/steam/search.png)

Once the <u>Terminal</u> is opened, type this command into the terminal and press <kbd>Enter</kbd>:

```
sudo apt install steam
```

![Terminal](/images/steam/steam2.png)

**Be very careful when using sudo with ANY Command. It can make system wide changes so be sure to read everything before entering 'Y'.**
Once installed, use the Activities Overview to search for and run <u>Steam</u>.


You can also use the Command Line tool `apt` to search for Steam:

```
apt search steam
```

![Terminal](/images/steam/steam1.png)

Once you find the right name for <u>Steam</u> you can install it with `apt`. This Command Line tool is useful for finding other applications as well.
