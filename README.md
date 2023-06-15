# Anatoly

This modpack is built using packwiz for seamless updates. Any existing instances will need adjusting to use the packwiz bootloader for Minecraft.

Further information regarding packwiz can be found [https://packwiz.infra.link/](https://packwiz.infra.link/)

## Manual Installation on existing instance
1. Head to [https://github.com/packwiz/packwiz-installer-bootstrap/releases](https://github.com/packwiz/packwiz-installer-bootstrap/releases) and download the latest release. Place the jar into your minecraft or .minecraft folder (this folder also contains options.txt)
2. Head to your instance setting, (Edit Instance -> Settings -> Custom commands), enable Custom Commands and paste the following command into the pre-launch command field.
```"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://krashd.github.io/minecraft-anatoly/pack.toml```
3. Remove all of your mods and resource packs for this instance.

## Portable JKDs for computers without admin rights.
* [openJDK 19.0.2-x64](https://download.java.net/java/GA/jdk19.0.2/fdb695a9d9064ad6b064dc6df578380c/7/GPL/openjdk-19.0.2_windows-x64_bin.zip)
