# TabeebHub — Downloads

Official installer downloads for **TabeebHub**, clinic management software.

> This repository contains distribution binaries only. **No source code is published here.**

---

## Download

### Windows

**[⬇ Download TabeebHub for Windows](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest/download/TabeebHub-Setup.exe)**

Windows 10 or Windows 11, 64-bit. Roughly 91 MB.

This link always serves the newest version — it does not need updating when a new release ships.

---

## Installing on Windows

1. Click the download link above and wait for the file to finish downloading.
2. Open **TabeebHub-Setup.exe**.
3. **Windows will show a blue warning screen.** This is expected — see below.
4. Choose the install location (or accept the default) and click **Install**.
5. TabeebHub installs for the current user only. **No administrator password is required.**

### About the "Windows protected your PC" warning

When you open the installer, Windows SmartScreen will show:

> **Windows protected your PC**
> Microsoft Defender SmartScreen prevented an unrecognized app from starting.

**To continue: click "More info", then click "Run anyway".**

This warning does **not** mean the file is unsafe or damaged. Windows shows it for any
application it has not yet seen downloaded many times. It will disappear on its own as
more clinics install TabeebHub.

If your clinic's IT policy blocks unrecognised applications, give your IT administrator
the checksum below — it lets them confirm the file is exactly the one we published.

---

## Verifying the download (for IT administrators)

Every release includes a `SHA256SUMS.txt` file listing the expected hash.

**Windows (PowerShell):**

```powershell
Get-FileHash .\TabeebHub-Setup.exe -Algorithm SHA256
```

**macOS / Linux:**

```bash
shasum -a 256 TabeebHub-Setup.exe
```

Compare the result against `SHA256SUMS.txt` on the [latest release page](https://github.com/abdullahbayomy/tabeebhub-releases/releases/latest).
If they match, the file is byte-for-byte what we published.

---

## Previous versions

Every release is kept permanently. Browse them on the
[Releases page](https://github.com/abdullahbayomy/tabeebhub-releases/releases) if you
need to reinstall a specific version.

---

## Support

Questions, or trouble installing? Contact **support@tabeeb-hub.com** or your clinic
administrator.

Website: [tabeeb-hub.com](https://tabeeb-hub.com)

---

Copyright © TabeebHub. All rights reserved.
