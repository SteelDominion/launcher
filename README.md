<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/program_info/net.steeldominion.SteelLauncher.logo-darkmode.svg">
  <source media="(prefers-color-scheme: light)" srcset="/program_info/net.steeldominion.SteelLauncher.logo.svg">
  <img alt="Steel Launcher" src="/program_info/net.steeldominion.SteelLauncher.logo.svg" width="40%">
</picture>
</p>

<p align="center">
  Steel Launcher is a custom launcher for Steel Dominion that allows you to easily manage multiple installations of Minecraft at once.<br />
  <br />This is a <b>fork</b> of the Prism Launcher and is <b>not</b> endorsed by it.
  <br />Prism Launcher is also a fork of MultiMC and is <b>not</b> endorsed by it.
</p>

## Installation

- All downloads and instructions for Steel Launcher can be found in the [releases page](https://github.com/SteelDominion/launcher/releases).
- Last build status can be found in the [GitHub Actions](https://github.com/SteelDominion/launcher/actions) tab.

- **Our Discord server:** [Steel Launcher Discord server](https://discord.gg/CsrQM8P5yy)

## Forking/Redistributing/Custom builds policy

You are free to fork, redistribute and provide custom builds as long as you follow the terms of the [license](LICENSE) (this is a legal responsibility), and if you made code changes rather than just packaging a custom build, please do the following as a basic courtesy:

- Make it clear that your fork is not Steel Launcher and is not endorsed by or affiliated with the Steel Launcher project.
- Go through [CMakeLists.txt](CMakeLists.txt) and change Steel Launcher's API keys to your own or set them to empty strings (`""`) to disable them (this way the program will still compile but the functionality requiring those keys will be disabled).

If you have any questions or want any clarification on the above conditions please make an issue and ask us.

Note that if you build this software without removing the provided API keys in [CMakeLists.txt](CMakeLists.txt) you are accepting the following terms and conditions:

- [Microsoft Identity Platform Terms of Use](https://docs.microsoft.com/en-us/legal/microsoft-identity-platform/terms-of-use)
- [CurseForge 3rd Party API Terms and Conditions](https://support.curseforge.com/en/support/solutions/articles/9000207405-curse-forge-3rd-party-api-terms-and-conditions)

If you do not agree with these terms and conditions, then remove the associated API keys from the [CMakeLists.txt](CMakeLists.txt) file by setting them to an empty string (`""`).

## License [![https://github.com/PrismLauncher/PrismLauncher/blob/develop/LICENSE](https://img.shields.io/github/license/PrismLauncher/PrismLauncher?label=License&logo=gnu&color=C4282D)](LICENSE)

All launcher code is available under the GPL-3.0-only license.
