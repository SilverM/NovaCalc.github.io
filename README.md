# NovaCalc — Modern Calculator for iOS

NovaCalc is a clean, fast calculator with a polished design and optional Scientific mode. It features a scrollable scientific keypad, Rad/Deg toggle, memory functions, operator highlighting, and subtle haptics for a delightful experience.

## Features

- Clean, focused UI
  - Large monospaced display for clear, readable numbers
  - Pinned display and mode controls; keypad scrolls when in Scientific mode
  - Operator highlighting for active operations
- Scientific mode (optional)
  - Trigonometry: sin, cos, tan (Rad/Deg toggle)
  - Logarithms: ln, log10
  - Roots and powers: √, x², xʸ
  - Constants: π, e
- Smart input behavior
  - AC/C behavior (C clears entry; AC resets all)
  - Repeated equals repeats last operation
  - Error handling (e.g., division by zero shows “Error”)
- Memory functions
  - MC, MR, M+, M− with an “M” badge when memory is non-zero
- Haptics
  - Light haptic feedback on key taps (toggleable in code)

## Screenshots

Include screenshots demonstrating:
- Normal mode (portrait)
- Scientific mode (portrait, showing scrollable keypad)
- Landscape (if supported)
- Operator highlighting and memory indicator

Recommended sizes: iPhone 6.7″, 6.5″, 5.5″. Use Xcode Previews or simulator.

## Requirements

- iOS target: iOS 16+ (adjust if needed)
- Xcode: 15+ (or your project’s version)
- SwiftUI

## Building

1. Open the project in Xcode.
2. Set your Team and Bundle Identifier:
   - Targets > App Target > Signing & Capabilities
   - Select your Apple Developer Team
   - Ensure a unique Bundle Identifier (e.g., com.yourname.NovaCalc)
3. Run on a simulator or device.

## App Icon

- Provide a 1024×1024 PNG (no transparency, square corners).
- Assets.xcassets > AppIcon:
  - If there’s an “iOS Marketing” slot, drop your 1024×1024 there.
  - Otherwise, add a new App Icon set or generate missing sizes with an icon tool.
- Target > General > App Icons: Set “App Icons Source” to your AppIcon set.

## App Store Submission Checklist

- App Store Connect
  - Create an app record with the same Bundle ID as in Xcode
  - Fill metadata: name, subtitle, description, keywords, category
  - Upload screenshots (portrait/landscape as applicable)
  - Privacy: Fill App Privacy questionnaire accurately
  - Support URL: Provide a simple support page (GitHub Pages / Notion / Google Sites)
- Versioning
  - Marketing Version (e.g., 1.0) and Build number (increment each upload)
- Archive and Upload
  - Xcode > Product > Archive
  - Organizer > Distribute App > App Store Connect
  - Wait for “Processing” in App Store Connect
  - Attach build to the version and Submit for Review

## How to Use (User Guide)

- Normal vs Scientific
  - Tap the pill at the top to switch modes. In Scientific mode, the extra keys appear above the standard keypad. Scroll if needed.
- Angle Mode
  - Tap the Rad/Deg pill to switch between radians and degrees for trig functions.
- Memory
  - MC: Clear memory
  - MR: Recall memory to display
  - M+: Add display to memory
  - M−: Subtract display from memory
- Input Tips
  - C clears the current entry; AC resets everything
  - Press = repeatedly to apply the last operation again
  - Long-press C to force AC (full reset)

## Roadmap (Optional)

- History tape with copy/share
- Themes (light/dark variants, accent colors)
- Scientific extensions (factorial, ^2, ^3, 10^x, 2^x, sinh/cosh/tanh)
- Programmer mode (hex/dec/bin, bitwise ops)
- Widgets and App Intents (quick calculations via Spotlight/Siri)

## Support

- Email: audioanalyticsauthority@gmail.com
  
## Privacy

NovaCalc does not collect personal data. If this changes, we’ll update this document and our App Store listing.

## License

Copyright © 2025 Your Name. All rights reserved.
