# com.apple.AdLib

Some config around Advertissments behavior

**See:** [Jamf discussion](https://www.jamf.com/jamf-nation/discussions/29821/macos-limit-ad-tracking)

```bash
echo "User: Ad Tracking: Enabling 'Limit Ad Tracking' in 'Security & Privacy'"
defaults write /Users/$user/Library/Preferences/ByHost/com.apple.preference.security.privacy limitAdTrackingCached -int 0
defaults write /Users/$user/Library/Preferences/com.apple.AdLib forceLimitAdTracking -int 1
defaults write /Users/$user/Library/Preferences/com.apple.AdLib "AD_DEVICE_IDFA" -string "00000000-0000-0000-0000-000000000000"
killall adprivacyd
killall -SIGHUP cfprefsd
```

**Not tested yet**

## Keys

```
CKDPIDSyncState = 0;
adprivacydMaxSegmentSendInterval = 259200;
adprivacydSegmentInterval = 54766;
allowApplePersonalizedAdvertising = 1;
allowIdentifierForAdvertising = 1;
"partiality-segment" = "https://partiality.itunes.apple.com/WebObjects/MZPartiality.woa/wa/IAD/segment";
personalizedAdsMigrated = 1;
```

## See also

- [com.apple.preference.security.privacy](com.apple.preference.security.privacy.md)