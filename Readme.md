# lockd0wn (iOS)

lockd0wn is an Open Source firewall for your iOS device. This project is a frok of the original [https://github.com/confirmedcode/lockdown-ios](Lockdown) without the VPN service and built-in [https://www.appconfig.org/](AppConfig) functionality. As this app should protect users it does not contain any telemetry or tracking.

### Stripped
- Lockdown VPN (LockdownTunnel)
- Lockdown VPN Widget
- Lockdown Firewall Widget
- [https://github.com/Velocet/lockdown-ios/blob/3fa8ce8f79678c224822b4b66b730bf70ea6852e/WhitelistUtilities.swift#L67](Domain Whitelist)

## Feedback

If you have any questions, concerns or other feedback, please let me know in the Issues.

## Roadmap

This app follows the official Lockdown for iOS roadmap/development. For any feature requests or bug reports, please create an issue on the [https://github.com/confirmedcode/lockdown-ios/issues](Lockdown for iOS Github repository).

## How To Build
- 'pod install'
- 'carthage update --no-use-binaries --platform ios'
- Open the ```*.xcworkspace``` file to build
- To sign the app, you will need an Apple Developer account

## License

This project is licensed under the *GNU General Public License v3.0* (GPL v3.0) License - see the [LICENSE.md](LICENSE.md) file for details.
