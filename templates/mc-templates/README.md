---
description: Find all the information about my Minecraft server templates
---

# Minecraft Templates

### Templates

* [x] Fabric 1.16.5
* [x] Fabric 1.17.1
* [ ] Fabric 1.18.1
* [x] Paper 1.8.8
* [x] Purpur 1.16.5
* [x] Purpur 1.17.1
* [ ] Purpur 1.18.1

{% hint style="warning" %}
I did not make any of the plugins, mods, or server software in the templates, please see [this page](sources.md) for sources.
{% endhint %}

### Downloading the template

1. Go to the [Builds actions page](https://github.com/srnyx/mc-server-templates/actions/workflows/builds.yml) on the GitHub
2. Click on the version you want to download from the left sidebar (ex: Purpur 1.16.5 Builds)
3. Click on the latest workflow run (the one at the top), make sure it has a green circle (if it's orange/yellow, wait for it to finish. If it's red, [contact srnyx](https://srnyx.xyz/discord))
4. Scroll down to where it says `Artifacts`
5. Click on the artifact (ex: Purpur 1.16.5) to download it
6. Find the downloaded ZIP on your computer and extract the files

![Step 2](<../../.gitbook/assets/actions-types.png>)
![Step 3](<../../.gitbook/assets/actions-types-latest.png>)
![Step 4/5](<../../.gitbook/assets/actions-types-artifacts.png>)

{% hint style="info" %}
If you need help, please join my [Discord server](https://srnyx.xyz/discord) and open a ticket via #support.
{% endhint %}

### Starting your server

1. Open the server's folder
2. Run either `start.bat` (Windows) or `start.sh` (other operating systems)
3. The server will not start because you need to accept the EULA
4. Open the `eula.txt` file in the server's folder and change `eula=false` to `eula=true`

{% hint style="danger" %}
You MUST accept the EULA to use your server. Please read through it carefully.
{% endhint %}
