---
description: This tutorial will guide you through the installation of Modded Debian XFCE
---

# Debian XFCE

Debian is the most stable and easy-to-use Linux system and while being combined with XFCE it also gives you the most possible performance along with the good amount of chance to modify the UI. Debian XFCE is good to go if you are looking for performace and stability.

## Pre-requisites

* You need to login into Andronix either with your Google account or email \(register if you already have an account\). Worried about your privacy? Read more [here](https://andronix.app/privacy-policy/).
* After logging in, click on the Install button of your favourite distro.
* If you haven't already purchased the distro, the app will prompt you to buy it first. You can proceed to the next step, if you already own the distro you want to install, else you can proceed to buy it.

{% hint style="info" %}
Modded OS are a **life-time purchases** and can be used on any number of devices.
{% endhint %}

_If already bought, the app will generate a one-time code for you to download the OS._

## Installation

* That's it, let's proceed to the actual installation now. Click on the **Copy** button and paste the copied code in a **Termux shell**.
* Let it finish. The installation will take some time as these are much bigger than the normal \(un-modded OS\) because these have things pre-installed.

{% hint style="warning" %}
If the **download is slow** for you, please try to download using a **VPN** in the European Union.
{% endhint %}

* When the download and extraction will finish, your termux will look something like this-

![](../../.gitbook/assets/complete_install_moddedos%20%281%29.png)

* You now need to start the distro with the following command

```text
./start-androdebian.sh
```

![](../../.gitbook/assets/start_moddedos.png)

* This will start the post-installation process i.e. setting up the essential packages. You will need to wait until this finishes.
* If the post-installation setup successfully executed, you will see a **blue screen** asking for a _username._ You can choose any username unless that's a reserved keyword like _admin, root etc._ \(your name works fine\). Press **Enter** to proceed.

{% hint style="info" %}
If you can't access your keyboard for entering the username, press the **ESC** key at the bottom. This restarts the script and this time make sure that you have your keyboard out \(click anywhere on the terminal\) when you're in the Termux shell.
{% endhint %}

![](../../.gitbook/assets/username_user%20%282%29.png)

* The second thing the script asks for is your name. This can be anything to like. Again press **Enter** to proceed.

{% hint style="danger" %}
While selecting your username make sure that you dont enter any Linux reserved usernames such as **root, admin, etc.** Also try to avoid the use of special characters in the username. If you break any rule for naming a user according to Linux, you might end up in an infinite process at the end of the installer.
{% endhint %}

* Next you need a **Password**. You can choose any password as long as it is longer than 6 characters. Press **Enter** to proceed. Confirm the password by re-entering it and press enter to continue.

![](../../.gitbook/assets/pass_user%20%282%29.png)

* Now you need a **Root Password.** You can choose any password as long as it is longer than 6 characters. Press **Enter** to proceed. Confirm the root password by re-entering it and press enter to continue.
* The next screen will show all the information entered. Check if those are the correct passwords and username \(if not, press _esc or back button_ to restart the script\). Press **Enter** to proceed.

![](../../.gitbook/assets/confirm_user.png)

* Now, wait until the system is creating the user. You should see something like this while the system is setting-up the user.

![](../../.gitbook/assets/user_creation_moddedos%20%282%29.png)

* That's it! After this finishes, you will see-

```bash
{your_username}@localhost:~$
```

![](../../.gitbook/assets/after_user%20%282%29.png)

* You can now continue to start the VNC server with the guide here to use the GUI.

