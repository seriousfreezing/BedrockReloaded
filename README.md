![Banner](https://i.imgur.com/LqwCXMR.png)

**Bedrock Reloaded** is a modpack designed entirely as an alternative to the Bedrock edition of Minecraft. It brings several improvements and features such as: **Improved interfaces**, fade in when loading chunks, enhanced particles, support for controllers and touchscreen, connect to **any Bedrock edition server** and much more!
### Looking to fork or use assets from my modpack? [Click here!](https://github.com/seriousfreezing/BedrockReloaded/wiki/Forks)

# 📥 Installation Guide
<details>
<summary>Client-side</summary>

- [ATLauncher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/361)
- [CurseForge Launcher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/160)
- [GDLauncher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/142)
- [Modrinth Launcher](https://support.modrinth.com/en/articles/8802250-modpacks-on-modrinth)
- [MultiMC](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/141)
</details>

> [!WARNING]
> Back up your server before you do anything.

<details>
<summary>Server-side</summary>

  - [Docker Compose](https://docker-minecraft-server.readthedocs.io/en/latest/)
  - [mcman](https://github.com/ParadigmMC/mcman)
- <details>
  <summary>Packwiz</summary>

  1. Download the [packwiz-installer-bootstrap](https://github.com/packwiz/packwiz-installer-bootstrap/releases);
  2. Then move it to the root folder of your server; 
  - It's the same folder as the ``fabric-server-1.xx.x-0.1x.x.jar`` file.
  3. Go to ``pre-launch command`` and add this command: 
  ```
  java -jar packwiz-installer-bootstrap.jar -g -s server https://raw.githubusercontent.com/seriousfreezing/BedrockReloaded/refs/heads/main/versions/supported/1.21.1/index.toml
  ```
    - [You can switch to the version of Minecraft you want;](https://github.com/seriousfreezing/BedrockReloaded/tree/main/versions/supported)
    - If you can't find it, maybe your server provider doesn't support it.

    **If you have any problems or questions, go to the [Packwiz wiki](https://packwiz.infra.link/tutorials/creating/getting-started/) or contact them on their [discord server.](https://discord.gg/DcSkRF4)**
  </details>
</details>

# 🙌 Credits
- The modpack is based on **[Adrenaline](https://modrinth.com/modpack/adrenaline) and [Simply Optimized](https://modrinth.com/modpack/sop)**;
- The descriptions and the wiki are inspired by the projects: **[Adrenaline](https://modrinth.com/modpack/adrenaline), [Fabulously Optimized](https://modrinth.com/modpack/fabulously-optimized) and [Sodium](https://modrinth.com/mod/sodium)**;
- The player's head icon on the pause screen was made thanks to **[MCHeads](https://mc-heads.net/)**!
- Some features are from other resource packs:
  - [3D Item Icons](https://modrinth.com/resourcepack/3d-items-mintynoura) by [mintynoura](https://modrinth.com/user/mintynoura)
  - [Bedrock weather](https://modrinth.com/resourcepack/bedrock-weather) by [mineland](https://modrinth.com/user/mineland)
  - [Environmental Water](https://modrinth.com/resourcepack/environmental-water) by [AgentMindStorm](https://modrinth.com/user/AgentMindStorm)
  - [Ore UI Expanded](https://modrinth.com/resourcepack/ore-ui-expanded) by [DiamondIsntHere](https://modrinth.com/user/DiamondIsntHere)
  - [Translations for Sodium](https://modrinth.com/resourcepack/translations-for-sodium) by [robotkoer](https://modrinth.com/user/robotkoer)
  - [Vanilla Tweaks](https://vanillatweaks.net/share#KZtWpI) by [The Vanilla Tweaks team](https://vanillatweaks.net/about/)

# 📜 License
This modpack is licensed under the GNU General Public License v3;

However, some of the artwork is licensed under Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International, see [this article](https://github.com/seriousfreezing/BedrockReloaded/wiki/Forks) for more information.