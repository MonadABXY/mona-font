![Banner](./docs/readme-banner.png)

[English](./README.md) | [한국어](./README-KO.md)

# Mona Font

Mona Font is a pixel-style font that supports multilingual text, special symbols, and emojis.

## Features

- **Localized Forms**: Supports region-specific CJK Ideographs using the OpenType `locl` feature.
- **Kerning**: Kerning is applied to Latin characters for better readability.
- **Emoji Support**: Includes both Color Emojis and Monochrome Emojis.

## Font Preview

[Try it out](https://monadabxy.com/fonts/mona/)

### Mona12

![Mona12 Preview](./docs/readme-preview-12.png)

### Mona12 Bold

![Mona12 Bold Preview](./docs/readme-preview-12-bold.png)

## Download

[Download Latest Version](https://github.com/MonadABXY/mona-font/releases/latest)

Please choose the appropriate font file for your needs.

| File Name                  | Description                                                                         |
| :------------------------- | :---------------------------------------------------------------------------------- |
| **Mona12.ttf**             | Integrated Font (Text + Emoji)                                                      |
| **Mona12Text{Region}.ttf** | Text-Only Font with fixed regional glyphs (for environments without `locl` support) |
| **Mona12ColorEmoji.ttf**   | Color Emoji Only                                                                    |
| **Mona12Emoji.ttf**        | Monochrome Emoji Only                                                               |

## Webfont Usage

### `<link>`

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/MonadABXY/mona-font/web/mona.css" />
```

### `@import`

```css
@import url("https://cdn.jsdelivr.net/gh/MonadABXY/mona-font/web/mona.css");
```

## Coverage

| Category              | Mona10 | Mona10 Bold | Mona12 | Mona12 Bold |
| --------------------- | ------ | ----------- | ------ | ----------- |
| Hangul Syllables      | ❌     | ❌          | ✅     | ✅          |
| Latin                 | ❌     | ❌          | ✅     | ✅          |
| CJK Ideographs        | ❌     | ❌          | ✅     | ⚠️          |
| Hiragana / Katakana   | ❌     | ❌          | ✅     | ✅          |
| Greek                 | ❌     | ❌          | ✅     | ❌          |
| Cyrillic              | ❌     | ❌          | ✅     | ❌          |
| Symbols / Punctuation | ❌     | ❌          | ✅     | ❌          |
| Monochrome Emoji      | ❌     | -           | ✅     | -           |
| Color Emoji           | ❌     | -           | ✅     | -           |

You can check the detailed list of supported characters below.

[Detailed Glyph List](./docs/GLYPHS.md)

## License & Credits

### License

**Mona Font** is released under the [SIL Open Font License 1.1](https://openfontlicense.org/).

It can be freely used, modified, and redistributed by anyone, including personal and corporate users.

However, selling the font file itself is prohibited.

- [OFL 1.1 Original Text](./OFL.txt)
- [OFL 1.1 Korean Translation](./OFL-KO.txt)

### Credits & Open Source Notice

#### 1. Google Noto Emoji

- **Usage**: Color palette and Flag emojis
- **License**: SIL Open Font License 1.1 (Fonts) / Apache License 2.0 (Tools/Images)
- **Source**: [googlefonts/noto-emoji](https://github.com/googlefonts/noto-emoji)

#### 2. Ark Pixel Font

- **Usage**: Glyphs in the CJK Ideographs area
- **License**: SIL Open Font License 1.1
- **Source**: [TakWolf/ark-pixel-font](https://github.com/TakWolf/ark-pixel-font)

#### 3. PixelMplus (M+ Fonts)

- **Usage**: Reference for Japanese and certain related symbols; some CJK ideograph glyphs
- **License**: M+ FONT LICENSE
- **Source**: [itouhiro/PixelMplus](https://github.com/itouhiro/PixelMplus)
