# Haven Display downloads

Official downloads for **Haven Display**, a free Windows utility by [Vaeltryn Studios](https://vaeltrynstudios.com/) for managing your display settings and wallpapers.

**[Download the latest version](https://github.com/Vaeltryn-Studios/haven-display-releases/releases/latest)**

This repository holds release files only. Haven Display's source code is not published here.

## What you need

- Windows 11 x64
- No administrator rights, internet connection or extra software

## Checking your download

Each release includes a checksum file. In PowerShell, run:

```powershell
Get-FileHash .\HavenDisplay-Setup-1.1.0-x64.exe -Algorithm SHA256
```

The result should match the value in `SHA256SUMS-1.1.0.txt`.

Haven Display is not code-signed, so your browser or Windows SmartScreen may warn you when you download or run it. If you downloaded it from this page and the checksum matches, you can choose **More info → Run anyway** in the SmartScreen window. Please don't turn SmartScreen off. A computer managed by an employer or school may not allow it to run.

## Licence

Haven Display is free to use under the terms in [LICENSE.txt](LICENSE.txt). Third-party notices are in [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
