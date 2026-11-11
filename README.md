# Praelecta for desktop

Download the Praelecta desktop app for Windows, Mac and Linux.

[Praelecta](https://praelecta.ca) is an AI study companion for students. Record a lecture and it comes back
as a transcript, a plain-English summary, verified formulas and definitions, and flashcards, with a map of
what the exam will cover.

## Download

The easiest way is the download buttons at **[praelecta.ca](https://praelecta.ca)**, which pick the right
file for your computer. The same files are always available here:

| Your computer | File |
| --- | --- |
| Windows 10 or later | [Praelecta-Setup.exe](https://github.com/Thelaw247/praelecta-desktop/releases/latest/download/Praelecta-Setup.exe) |
| Windows, no installer (unzip and run) | [Praelecta-win.zip](https://github.com/Thelaw247/praelecta-desktop/releases/latest/download/Praelecta-win.zip) |
| Mac with Apple silicon (M1 or later), macOS 13 or later | [Praelecta-mac-arm64.dmg](https://github.com/Thelaw247/praelecta-desktop/releases/latest/download/Praelecta-mac-arm64.dmg) |
| Mac with an Intel chip, macOS 13 or later | [Praelecta-mac-x64.dmg](https://github.com/Thelaw247/praelecta-desktop/releases/latest/download/Praelecta-mac-x64.dmg) |
| Linux, any distribution | [Praelecta-linux.AppImage](https://github.com/Thelaw247/praelecta-desktop/releases/latest/download/Praelecta-linux.AppImage) |
| Ubuntu, Debian, Mint | [Praelecta-linux.deb](https://github.com/Thelaw247/praelecta-desktop/releases/latest/download/Praelecta-linux.deb) |

Older versions are on the [releases page](https://github.com/Thelaw247/praelecta-desktop/releases).

## If your computer warns you

- **Windows:** SmartScreen or your antivirus may warn about an unknown publisher. Choose **More info**, then
  **Run anyway**. If the installer is blocked completely, use `Praelecta-win.zip`: it is the same app without
  an installer.
- **Mac:** the first time you open the app, macOS may block it. Open **System Settings > Privacy & Security**
  and click **Open Anyway**.

## Check your download

Every release includes `SHA256SUMS.txt`, a checksum for each file. To check a download on Windows:

```powershell
Get-FileHash .\Praelecta-Setup.exe -Algorithm SHA256
```

On Mac or Linux:

```sh
shasum -a 256 Praelecta-mac-arm64.dmg
```

The result should match the line for that file in `SHA256SUMS.txt`.

## About this repository

This repository holds only the finished installers. The app's source code is not public.

- Terms: https://praelecta.ca/terms
- Privacy: https://praelecta.ca/privacy

Praelecta is proprietary software. See [LICENSE.md](LICENSE.md).
