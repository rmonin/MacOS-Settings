# com.apple.commerce

## Keys

| key                       | value type |
|---------------------------|------------|
| PurchasesInflight         | bool       |
| AutoUpdate                | bool       |
| AutoUpdateRestartRequired | bool       |

```bash
# Turn on app auto-update
defaults write com.apple.commerce AutoUpdate -bool true

# Allow the App Store to reboot machine on macOS updates
defaults write com.apple.commerce AutoUpdateRestartRequired -bool true
```

## See also

- [com.apple.SoftwareUpdate](com.apple.SoftwareUpdate.md) - _Does still exist ?_
- [com.apple.AppStore](com.apple.AppStore.md)
