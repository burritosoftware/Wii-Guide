---
title: "cIOS"
---

{% include toc title="Table of Contents" %}

This tutorial will tell you how to install cIOS (custom IOS). This is required if you want to load games with a USB Loader. Some homebrew might work better using cIOS.

![d2x cIOS Installer](/images/cios/cIOS.png)

If you have a Wii mini, install [this cIOS](cios-mini) instead. Attempting to install any other cIOS on a Wii mini won't work.
{: .notice--info}

#### 你需要的是

* A Wii with an Internet connection
* An SD card or USB drive
* [d2x cIOS Installer](/assets/files/d2x-cIOS-Installer-Wii.zip)

Ensure that if you are using an SD card, the lock switch is in the unlocked position, otherwise you will not be able to select the correct options in the installer
{: .notice--warning}

#### 步骤

##### Section I - Downloading

1. Download d2x cIOS Installer and extract it to the `apps` folder on your SD card or USB drive.
1. Insert your SD card or USB drive into your Wii, and launch d2x cIOS Installer from the Homebrew Channel.

##### Section II - Installing

1. Press continue, then set the options to the following:
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 57
Select cIOS slot: 249
Select cIOS version: 65535
```
![Install cIOS 249](/images/cios/Install249.png)
1. Once set, press A twice to install.
1. When done installing, press A to return, and set the options to the following:
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 56
Select cIOS slot: 250
Select cIOS version: 65535
```
![Install cIOS 250](/images/cios/Install250.png)
1. Once set, press A twice to install.
1. When done installing, press A to return, and set the options to the following:
```
Select cIOS: v10 beta52 d2x-v10-beta52
Select cIOS base: 38
Select cIOS slot: 251
Select cIOS version: 65535
```
![Install cIOS 251](/images/cios/Install251.png)
1. Once set, press A twice again to install, and then exit once done.

{% capture bruh %}
Although the majority of games should work straight away with the defaults, some may require using a specific cIOS to function, or to utilize certain features within the game.<br> Examples include:
* Using a keyboard in Animal Crossing: City Folk.
* Running SpongeBob's Boating Bash.

A more comprehensive (although still incomplete) list can be found [**here**](https://wiki.gbatemp.net/wiki/Wii_cIOS_base_Compatibility_List)<br> To change the cIOS used for a specific game, follow these instructions:
{% endcapture %}
<div class="notice--warning">{{ bruh | markdownify }}</div>

<button class="tablinks btn btn--large btn--primary" id="defaultOpen" onclick="openTab(event, 'usbloadergx')">USB Loader GX</button>
<button class="tablinks btn btn--large btn--info" onclick="openTab(event, 'wiiflow')">WiiFlow</button>

<div id="usbloadergx" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_24_Pdwrc!!Select the game that isn't working. !!crwdP_25_Pdwrc!!Click Settings. !!crwdP_26_Pdwrc!!Select <code>Game Load</code>. !!crwdP_27_Pdwrc!!Scroll down to <code>Game IOS</code>. !!crwdP_28_Pdwrc!!Enter the IOS slot to use.
  </p>
  
  <ul>
    <li>
      Try using 250 or 251, if 249 doesn't work. !!crwdP_29_Pdwrc!!Press ok and try to load the game.
    </li>
  </ul>
</div>

<div id="wiiflow" class="blanktabcontent">
  <p spaces-before="0">
    !!crwdP_30_Pdwrc!!Select the game that isn't working. !!crwdP_31_Pdwrc!!Click the gear icon. !!crwdP_32_Pdwrc!!Go to cIOS and use the arrows to select the IOS slot to use.
  </p>
  
  <ul>
    <li>
      Try using 250 or 251, if 249 doesn't work. !!crwdP_33_Pdwrc!!Press Save and try to load the game.
    </li>
  </ul>
</div>
##### Options once complete

[Continue to the Homebrew Browser](hbb)<br> The Homebrew Browser is a good place to get homebrew on your Wii. 你可以选择来安装。
{: .notice--info}

[继续 网站导览](site-navigation) 我们有许多你可能喜欢的其他教程。
{: .notice--info}

你现在可以以使用一些自制工具例如[USB Loader GX](usbloadergx)和[WiiFlow](wiiflow)。
{: .notice--info}

<script>
    let tabcontent = document.getElementsByClassName("blanktabcontent");
    let tablinks = document.getElementsByClassName("tablinks");!!crwd_CB_10_BC_dwrc!!</script>

