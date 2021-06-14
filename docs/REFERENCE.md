# macOS Default Values Command Reference

## chflags
change file flags

## defaults
Command line interface to a user's defaults.

**Tip:** Use `defaults domains` to to list all domains available. 

[List of some documented domains](defaults/DOMAINS.md)

## launchctl: 
Unload daemons/agents and generally control launchd

**Tip:** Use `launchctl list` to show the currently set values for `launchctl`.

## mdutil
Manage the metadata stores used by Spotlight

[mdutil man page](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man1/mdutil.1.html)

## nvram
Manipulate firmware NVRAM variables

**Tip:** Use `nvram -xp` to show all firmware variables in XML format.

[nvram man page](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man8/nvram.8.html)

## PListBuddy
Read and write values to plists

### PListBuddy help

[PlistBuddy man page](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man8/PlistBuddy.8.html)


## pmset
Manipulate power management settings

**Tips:**     
* Use `pmset -g` to show the currently settings.
* Use `pmset -g ps` to show power source info.

[pmset man page](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man1/pmset.1.html)

## scutil
Manage system configuration parameters 

[scutil man page](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man8/scutil.8.html)

## systemsetup
Configuration tool for certain machine settings in System Preferences.  

**Tip:** Use `systemsetup -printCommands` to show the available commands.

[systemsetup man page](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man8/systemsetup.8.html)

## tmutil
Time Machine utility

[tmutil man page](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man8/tmutil.8.html)
