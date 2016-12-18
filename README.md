# Ready Steady Pan CFGs
Configs for Ready Steady Pan

# Information

These configs are currently in testing and, though functional, are not finalised. We expect to also provide support for FlamingSarge's RSP Plugin before we can release it for preseason.

The current version is Version 1.7.3, updated last on 18th December 2016. The config was first used in Preseason of Season 3 of Ready Steady Pan. Please direct any queries directly about the configs either in the Issues of this repository or in the Ready Steady Pan [Discord](https://steamcommunity.com/linkfilter/?url=http://discord.gg/2Jzr43T).

We strongly recommend server owners to use the tftrue plugin if they can, along with the official RSP Plugin.

# Installation

Server owners should download the zip for this repository by clicking the green "Clone or Download" button on the top right, underneath "1 contributor." Then, you should copy the (unzipped) files to your server using FTP (or scp, sFTP, whatever protocol you use). Execute these configs by opening the console, providing an rcon password, and typing:

```
rcon exec rsp_koth
```

...or the name of the config required per map.

# Changelog

- 2nd December 2016
  - Imported the 1.6 configs, gave them visual changes. Will update again to 1.8 after testing.
- 3rd December 2016
  - Updated the whitelists using whitelist.tf, still need to test them and add sponsorship.
- 4th December 2016
  - After testing, found out configs don't work on Multiplay.
  - 4 rounds is too many, 3 is ideal, 30 minutes.
  - Whitelists weren't working.
- 13th December 2016
  - Stylistic changes to configs.
  - Added disclaimer to the stopwatch cfg to show that it is not meant to be used in Season 3.
- 14th December 2016
  - Updated whitelists.
- 16th December 2016
  - Timelimits updated.
  - Stopwatch is now back to the way it was.
- 18th December 2016
  - Added tftrue integration.
