# com.apple.Accessibility

Manage Accessibility tools configuration

## Keys

| key                                | value type |
|------------------------------------|------------|
| AXSClassicInvertColorsPreference   | bool       |
| AccessibilityEnabled               | bool       |
| AutomationEnabled                  | bool       |
| BrailleInputDeviceConnected        | bool       |
| CommandAndControlEnabled           | bool       |
| DarkenSystemColors                 | bool       |
| DifferentiateWithoutColor          | bool       |
| EnhancedBackgroundContrastEnabled  | bool       |
| FullKeyboardAccessEnabled          | bool       |
| FullKeyboardAccessFocusRingEnabled | bool       |
| GenericAccessibilityClientEnabled  | bool       |
| GrayscaleDisplay                   | bool       |
| InvertColorsEnabled                | bool       |
| KeyRepeatDelay                     | bool       |
| KeyRepeatEnabled                   | bool       |
| KeyRepeatInterval                  | string     |
| ReduceMotionEnabled                | bool       |
| SpeakThisEnabled                   | bool       |
| VoiceOverTouchEnabled              | bool       |

## Graphical

![System Preferences](/media/SystemPreferences.Accessibility.png)

Go to System Preferences > Accessibility

### VoiceOver

![Voice Over](/media/com.apple.Accessibility.VoiceOver.png)

```bash
# Depending of wich parameters are enable or not, should test before set theses
defaults write com.apple.Accessibility AccessibilityEnabled -bool true
defaults write com.apple.Accessibility ApplicationAccessibilityEnabled -bool true

# Enable VoiceOver
defaults write com.apple.Accessibility VoiceOverTouchEnabled -bool true
```

### Zoom

<!-- TODO -->

### Display

#### Display > Display

![Display - Display](/media/com.apple.Accessibility.Display.Display.png)

```bash
# Depending of wich parameters are enable or not, should test before set this
defaults write com.apple.Accessibility AccessibilityEnabled -bool true

# Inverts colors
defaults write com.apple.Accessibility InvertColorsEnabled -bool true

# Classic invert
defaults write com.apple.Accessibility AXSClassicInvertColorsPreference -bool true

# Increase contrast (if enabled, Reduce transparency must be enable too)
defaults write com.apple.Accessibility DarkenSystemColors -bool true
defaults write com.apple.Accessibility EnhancedBackgroundContrastEnabled -bool true

# Reduce transparency (Can improve perfs)
defaults write com.apple.Accessibility EnhancedBackgroundContrastEnabled -bool true

# Differentiate without color
defaults write com.apple.Accessibility DifferentiateWithoutColor -bool true
```

**Missing** `Menu bar size`, `Display contrast`

#### Display > Cursor

![Display - Cursor](/media/com.apple.Accessibility.Display.Cursor.png)
 
 <!-- TODO -->

#### Display > Color Filters

![Display - Color filters](/media/com.apple.Accessibility.Display.ColorFilters.png)
 
 <!-- TODO -->

### Spoken Content

<!-- TODO -->

### Descriptions

<!-- TODO -->

### Audio

<!-- TODO -->

### Captions

<!-- TODO -->

### Voice Control

<!-- TODO -->

### Keyboard

<!-- TODO -->

#### Keyboard > Hardware

<!-- TODO -->

#### Keyboard > Accessiblity Keyboard

<!-- TODO -->

### Pointer Control

<!-- TODO -->

#### Pointer Control > Mouse & Trackpad

<!-- TODO -->

#### Pointer Control > Alternative Control Methods

<!-- TODO -->

### Switch Control

<!-- TODO -->

#### Switch Control > General

<!-- TODO -->

#### Switch Control > Typing

<!-- TODO -->

#### Switch Control > Switches

<!-- TODO -->

#### Switch Control > Navigation

<!-- TODO -->

### Siri

<!-- TODO -->

### Shortcut

<!-- TODO -->

## Not yet Documented

- BrailleInputDeviceConnected
- CommandAndControlEnabled
- FullKeyboardAccessEnabled
- FullKeyboardAccessFocusRingEnabled
- GenericAccessibilityClientEnabled
- GrayscaleDisplay
- KeyRepeatDelay
- KeyRepeatEnabled
- KeyRepeatInterval
- ReduceMotionEnabled
- SpeakThisEnabled

## See also

- [com.apple.controlcenter](com.apple.controlcenter.md) "NSStatusItem Visible AccessibilityShortcuts" _show in menu bar
- ??? _show in control center_
