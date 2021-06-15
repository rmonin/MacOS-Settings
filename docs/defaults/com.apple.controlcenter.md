# com.apple.controlcenter
Menu Bar, Control Center config

## Keys
| key                                           | value type |
|-----------------------------------------------|------------|
| "NSStatusItem Visible AccessibilityShortcuts" | bool       |
| "NSStatusItem Visible Battery"                | bool       |
| "NSStatusItem Visible BentoBox"               | bool       |
| "NSStatusItem Visible Clock"                  | bool       |
| "NSStatusItem Visible DoNotDisturb"           | bool       |
| "NSStatusItem Visible Item-0"                 | bool       |
| "NSStatusItem Visible Item-1"                 | bool       |
| "NSStatusItem Visible Item-2"                 | bool       |
| "NSStatusItem Visible Item-3"                 | bool       |
| "NSStatusItem Visible Item-4"                 | bool       |
| "NSStatusItem Visible Item-5"                 | bool       |
| "NSStatusItem Visible Item-6"                 | bool       |
| "NSStatusItem Visible Item-7"                 | bool       |
| "NSStatusItem Visible KeyboardBrightness"     | bool       |
| "NSStatusItem Visible NowPlaying"             | bool       |
| "NSStatusItem Visible WiFi"                   | bool       |

## Sample
```
defaults write com.apple.appstore "NSStatusItem Visible WiFi" -bool true
defaults write com.apple.appstore "NSStatusItem Visible Bluetooth" -bool false
defaults write com.apple.appstore "NSStatusItem Visible AirDrop" -bool false
defaults write com.apple.appstore "NSStatusItem Visible KeyboardBrightness" -bool false
defaults write com.apple.appstore "NSStatusItem Visible ScreenMirroring" -bool false
defaults write com.apple.appstore "NSStatusItem Visible Display" -bool false
defaults write com.apple.appstore "NSStatusItem Visible Sound" -bool false
defaults write com.apple.appstore "NSStatusItem Visible NowPlaying" -bool false
defaults write com.apple.appstore "NSStatusItem Visible AccessibilityShortcuts" -bool false
defaults write com.apple.appstore "NSStatusItem Visible Battery" -bool true
```

## Further more
- [com.apple.airplay](com.apple.airplay.md) - _manage air play indicator in menu bar_
- show percentage battery ??? display
- spotlight ??? hide
- siri ??? hide
- time machine ??? hide

