# setdefprint

VB6 Make Default printer utility (`Project1`) that lists installed printers and sets the selected one as the Windows default (Win95 via `SetPrinter` level 5; WinNT via profile/`PrinterPorts`). Open `Project1.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Project1.vbp`) | VB6 | WinForms exe | Set the selected printer as the Windows default |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Project1.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `comdlg32.ocx`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/setdefprint`.
Company names in `.vbp` files: TSD.

## License

MIT © 2026 Vader Consulting for Dave Robinson's code. See `LICENSE`.
