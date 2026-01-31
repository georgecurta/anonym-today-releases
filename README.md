# anonym.today Desktop App

Official releases for the **anonym.today Desktop App** - Secure document anonymization powered by AI.

## Download

Download the latest version for your platform:

| Platform | Download |
|----------|----------|
| Windows (x64) | [anonym.today_1.0.0_x64-setup.exe](https://github.com/georgecurta/anonym-today-releases/releases/latest/download/anonym.today_1.0.0_x64-setup.exe) |
| macOS (Apple Silicon) | Coming soon |
| macOS (Intel) | Coming soon |
| Linux (AppImage) | Coming soon |
| Linux (DEB) | Coming soon |

Or visit the [Releases](https://github.com/georgecurta/anonym-today-releases/releases) page for all versions.

## Features

- **Multi-format Support**: PDF, DOCX, XLSX, TXT, CSV, JSON, XML
- **200+ Entity Types**: Comprehensive PII detection (names, addresses, SSN, credit cards, etc.)
- **27 Recognition Languages**: English, German, Spanish, French, and more
- **48 UI Translations**: Full interface localization
- **Secure Vault**: BIP39 24-word recovery phrase for encrypted local storage
- **Cross-platform**: Windows, macOS, Linux

## System Requirements

### Windows
- Windows 10 or later (x64)
- WebView2 Runtime (included in Windows 11, auto-installed on Windows 10)

### macOS
- macOS 10.15 (Catalina) or later
- Apple Silicon (M1/M2/M3) or Intel processor

### Linux
- Ubuntu 20.04+ or compatible distribution
- WebKitGTK 4.1+

## Installation

### Windows
1. Download `anonym.today_x.x.x_x64-setup.exe`
2. Run the installer
3. Follow the setup wizard
4. Launch from Start Menu or Desktop shortcut

### macOS
1. Download the `.dmg` file for your processor
2. Open the DMG and drag to Applications
3. On first launch, right-click and select "Open" to bypass Gatekeeper

### Linux
**AppImage:**
```bash
chmod +x anonym.today_x.x.x_amd64.AppImage
./anonym.today_x.x.x_amd64.AppImage
```

**DEB (Debian/Ubuntu):**
```bash
sudo dpkg -i anonym.today_x.x.x_amd64.deb
```

## Privacy & Security

- **Local Processing**: Documents are processed via the anonym.today API with end-to-end encryption
- **No Data Storage**: Your documents are never stored on our servers
- **Secure Vault**: Optional encrypted local storage with BIP39 recovery
- **Open Source UI**: The desktop app UI is open source

## Links

- **Website**: [anonym.today](https://anonym.today)
- **Documentation**: [Help & Guides](https://anonym.today/help)
- **Report Issues**: [GitHub Issues](https://github.com/georgecurta/anonym-today-releases/issues)

## License

The anonym.today Desktop App is proprietary software. See [LICENSE](LICENSE) for details.

---

Built with [Tauri](https://tauri.app) | Powered by [anonym.today](https://anonym.today)
