# com.apple.AppStore

## Keys

| key                                                        | value type |
|------------------------------------------------------------|------------|
| ASAcknowledgedOnboardingVersion                            | int        |
| AVPlayerViewShowsDurationInsteadOfTimeRemainingDefaultsKey | bool       |
| AutoPlayVideoSetting                                       | ?          |
| UserSetAutoPlayVideoSetting                                | bool       |
| WebKitDeveloperExtras                                      | bool       |
| ShowDebugMenu                                              | bool       |

```bash
# Enable the WebKit Developer Tools in the Mac App Store
defaults write com.apple.appstore WebKitDeveloperExtras -bool true

# Enable Debug Menu in the Mac App Store
defaults write com.apple.appstore ShowDebugMenu -bool true
```

## See also

- [com.apple.SoftwareUpdate](com.apple.SoftwareUpdate.md) - _Does still exist ?_
- [com.apple.commerce](com.apple.commerce.md)