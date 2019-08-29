# WorldEditSUI
[![Discord](https://img.shields.io/discord/489135856284729384.svg?label=Discord&logo=discord&logoColor=fff)](https://discord.gg/vGCUzHq)
[![Twitter](https://img.shields.io/twitter/follow/KennyTVN.svg?label=Twitter)](https://twitter.com/KennyTVN)

Sassy Minecraft plugin to show your current WorldEdit selection by displaying particles (which can be greatly customized in the plugin's config).
It aims at a higher performance and lesser memory impact by having a quite simplistic approach to calculating vectors.

You can read up on everything else and see examples on the [**Spigot page**](https://www.spigotmc.org/resources/worldeditsui.60726/).

## Compiling
You need the Spigot server version 1.8.8-R0.1-SNAPSHOT installed (i.e. BuildTools/compiled source) to be able to compile the project.
See the `without-1.8` branch to compile the project without it (done by simply dropping 1.8 support).

Use Maven to compile the project (`mvn clean package`).

## Licence
This project is licensed under the [GNU General Public License](http://www.gnu.org/licenses/gpl-3.0).
