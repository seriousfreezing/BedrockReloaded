![Banner](https://i.imgur.com/LqwCXMR.png)

**Bedrock Reloaded** is a modpack designed entirely as an alternative to the Bedrock edition of Minecraft. It brings several improvements and features such as: **Improved interfaces**, fade in when loading chunks, enhanced particles, support for controllers and touchscreen, connect to **any Bedrock edition server** and much more!

### Looking to fork or use assets from my modpack? [Click here!](https://github.com/seriousfreezing/BedrockReloaded/wiki/Forks)

# 📥 Installation Guide
<details>
<summary>Client-side</summary>

- [CurseForge Launcher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/160)
- [Modrinth Launcher](https://support.modrinth.com/en/articles/8802250-modpacks-on-modrinth)
- [MultiMC](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/141)
- [GDLauncher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/142)
- [ATLauncher](https://www.bisecthosting.com/clients/index.php?rp=/knowledgebase/361/)
</details>
<details>
<summary>Server-side (W.I.P)</summary>

  - [itzg/minecraft-server (Docker)](https://docker-minecraft-server.readthedocs.io/en/latest/)
- <details>
  <summary>Packwiz</summary>
  
  This guide uses ATLauncher as an example, you may be able to do this with other launchers but the step-by-step will change. To install the modpack from source, follow these steps:

    1. [Download this.](https://github.com/packwiz/packwiz-installer-bootstrap/releases)
    2. Create an instance for Minecraft 1.xx.x with Fabric.
    3. [Move the previously downloaded file to your instance folder.](https://i.imgur.com/7A3rAQM.png)
    4. Go to the instance settings and then to the commands tab.
    5. [Click on “Enable commands?” and add this command line to the pre-launch:](https://i.imgur.com/Jrn1VsU.png)

    - `"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/seriousfreezing/BedrockReloaded/refs/heads/main/versions/supported/1.21.1/index.toml`
    (Change to the version you want.)

    6. [Add the mods mentioned in the description to this repository folder:](https://i.imgur.com/oj6ilpB.png)
    `./versions/supported/1.xx.x/`

    - [Click here to be redirected](https://github.com/seriousfreezing/BedrockReloaded/tree/main/versions/supported)
    7. You're ready to play!

    **If you have any problems or questions, go to the [Packwiz wiki](https://packwiz.infra.link/tutorials/creating/getting-started/) or contact them on their [discord server.](https://discord.gg/DcSkRF4)**
  </details>
</details>