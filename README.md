# tsubasa-mac
Custom "App" for launching Tsubasa through [gbammc/Thor](https://github.com/gbammc/Thor) for a keyboard shortcut and a BitBar script on macOS

## Requirements
- [tsubasa](https://github.com/thebitstick/tsubasa)
- [gbammc/Thor](https://github.com/gbammc/Thor) * for keyboard shortcuts
- [matryer/bitbar](https://github.com/matryer/bitbar) * for the BitBar script

## Usage
Replace the path in each script with your relevant paths.  
Scripts:
- `Tsubasa Full.app/Contents/MacOS/Tsubasa Full`
- `Tsubasa Region.app/Contents/MacOS/Tsubasa Region`
- `Tsubasa Window.app/Contents/MacOS/Tsubasa Window`
- `tsubasa-bitbar.sh`

## Disclaimer for Info.plist
For each "app", is a Info.plist that was copied from an Electron app solely for being compatible with Thor. Nothing in the Info.plist is relevant other than the `CFBundleIconFile` key.
