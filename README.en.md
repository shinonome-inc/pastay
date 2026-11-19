<div align="center">

<img src=".github/icon.png" alt="Pastay icon" width="128" height="128">

# Pastay

**Catch secrets before you paste them into AI**

A Mac menu bar app that spots names, phone numbers, passwords and other sensitive info right before you paste it into AI or chat.<br>
Every check runs on your Mac.

[![Download for Mac](https://img.shields.io/badge/Download_for_Mac-Pastay.dmg-2F86F6?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/shinonome-inc/pastay/releases/latest/download/Pastay.dmg)

[![Latest release](https://img.shields.io/github/v/release/shinonome-inc/pastay?label=latest&color=5B4CF0)](https://github.com/shinonome-inc/pastay/releases/latest) ![macOS 14 or later](https://img.shields.io/badge/macOS-14%20or%20later-555555?logo=apple&logoColor=white) ![Apple silicon](https://img.shields.io/badge/Apple%20silicon-M1%20or%20later-555555)

[Website](https://pastay.shinonome.com/en) · [Releases](https://github.com/shinonome-inc/pastay/releases) · [Contact](https://github.com/shinonome-inc/pastay/issues)

**English** · [日本語](README.md)

</div>

> [!NOTE]
> The app is available in English and Japanese, and you can switch between them at any time. Phone numbers and My Number are detected in Japanese formats; email addresses, API keys, passwords, private keys and card numbers are detected regardless of language.

## Features

- **Alerts at the top of your screen** — When you copy or are about to paste something sensitive, an alert appears at the top of your screen, right by the camera
- **Pause ⌘V and paste it redacted** — Pastay stops the paste and lets you decide what to do. Choose “Paste Redacted” and sensitive parts are replaced with placeholders like `[Phone1]`
- **Choose how you're warned** — Pick “Just Let Me Know” or “Stop and Ask”, after trying out how each one looks
- **A clipboard history that stays safe** — Go back through up to 1,000 copied items with a shortcut. History is stored encrypted, and opening it asks for Touch ID
- **Works in any app** — ChatGPT, Claude, Gemini and other AI tools, plus Slack, email and more

## Privacy

- **Your content never leaves** — Neither what you copy nor the check results are ever sent anywhere. Even the AI that does the checking runs on your Mac
- **Encrypted history** — History is encrypted and kept on your Mac, with the key stored in your Keychain
- **No keylogging** — Accessibility permission is used only to notice when you press ⌘V

To improve the app, we send only usage statistics such as how often it's launched.

## Requirements

- macOS 14 or later
- A Mac with Apple silicon (M1 or later)
- For AI-powered checks, turn on Apple Intelligence or download the checking model from the app's settings

## Installation

1. Download [Pastay.dmg](https://github.com/shinonome-inc/pastay/releases/latest/download/Pastay.dmg) (also available from [Releases](https://github.com/shinonome-inc/pastay/releases/latest))
2. In the window that opens, drag `Pastay` into `Applications`
3. Open `Pastay` from the Applications folder, choose your language, and follow the guide to pick an alert style

The app checks for updates automatically (the “Updates” tab in Settings).

## Contact

Please use [Issues](https://github.com/shinonome-inc/pastay/issues). Don't include any real sensitive information.

## License

[License Agreement](LICENSE.md) · [Third-Party Notices](THIRD_PARTY_NOTICES.md)

The License Agreement is written in Japanese. The Third-Party Notices introduce each component in Japanese, with the license texts in their original English.

<div align="center">
<sub>© SHINONOME, K.K.</sub>
</div>
