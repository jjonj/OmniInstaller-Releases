# OmniInstaller for Windows

[**Download the latest Windows x64 release**](https://github.com/jjonj/OmniInstaller-Releases/releases/latest)

**Recommended:** download `OmniInstaller-Setup-win-x64.zip`, extract the ZIP, then double-click **Install.cmd**. This adds Start Menu shortcuts and offers a Desktop shortcut and opt-in tray startup. The app is self-contained; no .NET runtime or developer tools are required to install prebuilt software.

**Portable:** download `OmniInstaller-win-x64.exe`, rename it to `OmniInstaller.exe`, and run it from a permanent folder. Use the Settings page to set the optional Hub address or manually check for OmniInstaller updates. Updates never install automatically.

Within OmniInstaller, select an app/build method/path, then **Install**, **Update**, or **Remove**. Public GitHub Releases need no sign-in; private repos use existing Git/gh authorization, and source builds may require Git and their stated SDKs. OmniHub is optional; local GitHub installs work without Hub.

The release assets include a SHA256SUMS.txt file. The setup is currently unsigned (Windows may show a SmartScreen warning). This public repository hosts binary distributions only, not the OmniInstaller source code.