# A macOS Command Reference

**`chflags`** change file flags

**`defaults`** user's defaults system /
`defaults domains` all domains available /
[some documented domains](defaults/DOMAINS.md)

**`launchctl`** Unload daemons/agents and generally control launchd /
`launchctl list` currently set values

**`mdutil`** Manage the metadata stores used by Spotlight

**`nvram`** Manipulate firmware NVRAM variables /
`nvram -xp` all firmware variables

**`usr/libexec/PlistBuddy`** Useful for editing `CFBundleXXXX` file /
`usr/libexec/PlistBuddy --help` /
[samples](https://medium.com/@marksiu/what-is-plistbuddy-76cb4f0c262d) /
[samples](PlistBuddy/REFERENCE.md)

**`pmset`** Power management settings / `pmset -g` current settings / `pmset -g ps` power source info

**`scutil`** system configuration parameters 

**`systemsetup`** Some machine settings located in System Preferences /
`systemsetup -printCommands`

**`tmutil`** Time Machine utility
