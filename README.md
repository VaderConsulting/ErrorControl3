# ErrorControl3

VB6 v3 rewrite of Error Control (`ErrorControl.exe`) for Wise for Windows Installer 4.x error logs. Same Dave Robinson 2002 product lineage as ErrorControl, with MSI object library (`msi.dll`) added alongside common-dialog, MSINET, tab control, and WebBrowser UI.

**Source last updated:** 2002-06-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ErrorControl3` (`ErrorControl3.vbp`) | VB6 | WinForms exe | Wise MSI error log interpreter (v3) |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `ErrorControl3.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Microsoft Windows Installer Object Library (`msi.dll`)
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMDLG32.OCX`
  - `MSINET.OCX`
  - `Mscomctl.ocx`
  - `Tabctl32.ocx`
  - `shdocvw.dll`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/ErrorControl3`.
Company names in project files: Dave Robinson. Copyright 2002 Dave Robinson.

## License

MIT © 2026 Vader Consulting for Dave Robinson's code. See `LICENSE`.
