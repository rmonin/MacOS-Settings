# .macOS 

A nearly exhaustive .macos dotfile config inspired from [@mathiasbynens](http://mths.be/macos) work.

## Tested environment

```
$ sw_vers && system_profiler SPHardwareDataType -detailLevel mini
```

```
ProductName:	macOS
ProductVersion:	11.4
BuildVersion:	20F71
Hardware:

    Hardware Overview:

      Model Name: MacBook Air
      Model Identifier: MacBookAir10,1
      Chip: Apple M1
      Total Number of Cores: 8 (4 performance and 4 efficiency)
      Memory: 16 GB
      System Firmware Version: 6723.120.36
      OS Loader Version: 6723.120.36
```

## Repositories configuration
1. `master`: Reflects the fully configured .macos
2. `mathiasbynens`: Reflects http://mths.be/macos at all times. 
3. `rmonin`: My personal dotfile

## Usage
When setting up a new Mac, you may want to set some sensible macOS defaults:

```
./.macos
```

## Reference
Unsure of what you can modify or which commands to use?
Check out [REFERENCE.md](docs/REFERENCE.md).
