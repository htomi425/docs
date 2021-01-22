---
description: "Let's rock with the music! \U0001F3B8"
---

# サウンド 🎵

![](../.gitbook/assets/sound_banner.png)

You can **use your speakers** while using your distro to get all that nice music from Spotify \(or anything\) while you code. We use **Pulse Audio** to get that sound out of the PRoot container to your Android's speakers.

{% hint style="info" %}
**Modded OS** have sound output through phone's speakers enabled out of the box.
{% endhint %}

Just follow these steps correctly in order to have sound output enabled-

* Just **close** the distro if you have it opened with running _exit_ inside _**Termux.**_ Ignore this step if you haven't have your distro working.

```bash
exit
```

* Run the following command in Termux \(Not inside Linux\)

```bash
 pkg install wget && wget https://andronixos.sfo2.cdn.digitaloceanspaces.com/OS-Files/setup-audio.sh && chmod +x setup-audio.sh && ./setup-audio.sh
```

* This should enable you to have sound inside the distro.

{% hint style="warning" %}
Check the **volume level** before filing any bug report.
{% endhint %}

If you are still not able to get the audio output or the audio stops after a certain time then open a new Termux session and type:

```bash
pulseaudio --start
```

{% hint style="danger" %}
If you started the VNC and have not played any audio within **15minutes** of time span then audio server kills itself to prevent excessive battery drain.
{% endhint %}

