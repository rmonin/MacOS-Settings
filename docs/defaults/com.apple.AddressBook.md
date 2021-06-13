# com.apple.AddressBook

Some config keys for Address Book app

I suppose configs exec hidden keys are stored on iCloud. So, may config it graphicaly and sync it with iCloud 

## Keys

| key                                     | value type |
|-----------------------------------------|------------|
| ABBirthDayVisible                       | bool       |
| ABDefaultAddressCountryCode             | string     |
| ABUserHasSelectedDefaultCountryCode     | bool       |
| ABTextSizeIncrement                     | int        |
| ABInitialLabelsAddress                  | array      |
| ABInitialLabelsEmail                    | array      |
| ABInitialLabelsPhone                    | array      |
| ABInstantMessagesVisible                | bool       |
| ABTextSizeIncrement                     | int        |
| ABURLsVisible                           | bool       |
| "NSToolbar Configuration NSPreferences" | array      |
| ABShowDebugMenu                         | bool       |


## Hidden Configuration

```bash
# Enable the debug menu in Address Book
defaults write com.apple.addressbook ABShowDebugMenu -bool true
```