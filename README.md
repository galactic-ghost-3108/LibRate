# LibRate — public bundle

Everything a person needs to install LibRate and understand it, in one folder.
Share the whole folder phone-to-phone; it is meant to travel together.

| File | What it is |
|---|---|
| `01-What-is-LibRate-EN.pdf` · `01-What-is-LibRate-HI.pdf` | What LibRate is and why (English / हिन्दी) |
| `02-How-it-works.pdf` | Keys, frames, Bluetooth hops, relays, encryption — plain language |
| `03-Inside-the-app.pdf` | Every screen and setting, with the reasoning behind each design choice (e.g. why relay addresses are hidden) |
| `04-Architecture.pdf` | Components, wire format, routing, cryptography, storage, build, threat model — for engineers |
| `LibRate-1.0.0-arm64-v8a.apk` | The app, for most phones (64-bit) |
| `LibRate-1.0.0-armeabi-v7a.apk` | The app, for older / budget phones (32-bit) |
| `SHA256SUMS.txt` | Checksums of the two APKs |
| `src/` | HTML sources of the PDFs |

## Install

1. Open the APK that matches your phone (try the other if it refuses).
2. Allow installs from this source when Android asks — once.
3. Open LibRate, keep or edit your name, tap **Allow all**.

Updates installed over an existing copy keep all data. Uninstalling erases everything.

## Verify

Compare the APK's SHA-256 with `SHA256SUMS.txt` or a friend's copy. All genuine
releases are signed with this certificate:

```
7F:05:8A:F1:48:8C:A4:0A:AF:B2:14:86:D7:7A:64:24:19:9B:00:30:BB:38:A0:44:FA:11:B7:8D:7A:78:15:B6
```

Android refuses to install a differently-signed APK over an existing LibRate.

## Contact

Questions, relays, fresh download links: **keshavgithub01@gmail.com**

Source: https://github.com/Keshav-Kumar-Agastya/Librate