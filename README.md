# Mac UK Keyboard Layout for Windows

A Windows keyboard layout that replicates the Mac UK keyboard, including all Option (Alt) and Option+Shift key combinations.

## Features

- **All Mac Option key characters** – Type ©, ®, ™, €, £, ¥, and many more
- **All Mac Option+Shift characters** – Access †, ‡, °, ±, ≠, ≤, ≥, and others
- **Five dead keys for accented characters:**
  - `AltGr+E` → Acute (á, é, í, ó, ú, ý)
  - `AltGr+U` → Umlaut (ä, ë, ï, ö, ü, ÿ)
  - `AltGr+I` → Circumflex (â, ê, î, ô, û)
  - `AltGr+N` → Tilde (ã, ñ, õ)
  - `AltGr+`` ` → Grave (à, è, ì, ò, ù)
- **Direct access to ß** via `AltGr+S`
- **Direct access to ç** via `AltGr+C`
- **Curly quotes** via `AltGr+[` and `AltGr+]`
- **Non-breaking space** via `AltGr+Space`

## Usage

On Windows, the **Right Alt** key (also called **AltGr**) functions as the Mac's **Option** key.

### Quick Reference

#### Option (AltGr) Layer

| Key | Character | Key | Character | Key     | Character |
| --- | --------- | --- | --------- | ------- | --------- |
| `1` | ¡         | `Q` | œ         | `A`     | å         |
| `2` | ™        | `W` | ∑         | `S`     | ß         |
| `3` | £         | `E` | ´ (dead)  | `D`     | ∂         |
| `4` | ¢         | `R` | ®        | `F`     | ƒ         |
| `5` | ∞         | `T` | †         | `G`     | ©        |
| `6` | §         | `Y` | ¥         | `H`     | ˙         |
| `7` | ¶         | `U` | ¨ (dead)  | `J`     | ∆         |
| `8` | •         | `I` | ˆ (dead)  | `K`     | ˚         |
| `9` | ª         | `O` | ø         | `L`     | ¬         |
| `0` | º         | `P` | π         | `;`     | …         |
| `-` | –         | `[` | "         | `'`     | æ         |
| `=` | ≠         | `]` | '         | `` ` `` | ` (dead)  |
|     |           | `\` | «         |         |           |

| Key | Character | Key     | Character            |
| --- | --------- | ------- | -------------------- |
| `Z` | Ω         | `,`     | ≤                    |
| `X` | ≈         | `.`     | ≥                    |
| `C` | ç         | `/`     | ÷                    |
| `V` | √         | `Space` | (non-breaking space) |
| `B` | ∫         |         |                      |
| `N` | ˜ (dead)  |         |                      |
| `M` | µ         |         |                      |

#### Option+Shift (AltGr+Shift) Layer

| Key | Character | Key | Character | Key     | Character |
| --- | --------- | --- | --------- | ------- | --------- |
| `1` | ⁄         | `Q` | Œ         | `A`     | Å         |
| `2` | €         | `W` | „         | `S`     | Í         |
| `3` | ‹         | `E` | ´         | `D`     | Î         |
| `4` | ›         | `R` | ‰         | `F`     | Ï         |
| `5` | ﬁ         | `T` | ˇ         | `G`     | ˝         |
| `6` | ﬂ         | `Y` | Á         | `H`     | Ó         |
| `7` | ‡         | `U` | ¨         | `J`     | Ô         |
| `8` | °         | `I` | ˆ         | `K`     |           |
| `9` | ·         | `O` | Ø         | `L`     | Ò         |
| `0` | ‚         | `P` | ∏         | `;`     | Ú         |
| `-` | —         | `[` | "         | `'`     | Æ         |
| `=` | ±         | `]` | '         | `` ` `` | `         |
|     |           | `\` | »         |         |           |

| Key | Character | Key | Character |
| --- | --------- | --- | --------- |
| `Z` | ¸         | `,` | ¯         |
| `X` | ˛         | `.` | ˘         |
| `C` | Ç         | `/` | ¿         |
| `V` | ◊         |     |           |
| `B` | ı         |     |           |
| `N` | ˜         |     |           |
| `M` | Â         |     |           |

### Dead Keys

Dead keys let you type accented characters in two steps: press the dead key, then press the base letter.

| Dead Key   | Trigger     | Available Characters    |
| ---------- | ----------- | ----------------------- |
| Acute      | `AltGr+E`   | á é í ó ú ý Á É Í Ó Ú Ý |
| Umlaut     | `AltGr+U`   | ä ë ï ö ü ÿ Ä Ë Ï Ö Ü Ÿ |
| Circumflex | `AltGr+I`   | â ê î ô û Â Ê Î Ô Û     |
| Grave      | `AltGr+`` ` | à è ì ò ù À È Ì Ò Ù     |
| Tilde      | `AltGr+N`   | ã ñ õ Ã Ñ Õ             |

**Example:** To type "ü", press `AltGr+U`, release, then press `u`.

## Installation

1. Download the latest ZIP from the [Releases](https://github.com/matt-FFFFFF/Mac-UK-Keyboard-Layout-for-Windows/releases/latest) page. Extract the ZIP file and run the `setup.exe` installer.
2. Follow the on-screen instructions to complete the installation.
3. Go to Settings → Time & Language → Language → Keyboard
4. Add "United Kingdom (Mac)" as an input method
5. Use <kbd>Win</kbd> + <kbd>Space</kbd> to switch between keyboard layouts

## Building from Source

1. Install the [Microsoft Keyboard Layout Creator (MKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134).
1. Open the `Mac-UK-Windows.klc` file in MKLC.
1. Make your changes
1. Go to `Project` > `Build DLL and Setup Package`

## Acknowledgements

Inspired by [dotcore/Mac-US-Keyboard-Layout-for-Windows](https://github.com/dotcore/Mac-US-Keyboard-Layout-for-Windows).

## Contributing

Contributions are welcome!
If you find any issues or have suggestions, please open an issue or submit a pull request.
