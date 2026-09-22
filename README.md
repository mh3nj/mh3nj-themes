![Mh3nj Themes](screenshots/banner.png)

# Mh3nj Themes

[![License](https://img.shields.io/github/license/mh3nj/mh3nj-themes?color=blue)](LICENSE)
[![Version](https://img.shields.io/github/v/release/mh3nj/mh3nj-themes?color=green&label=version)](https://github.com/mh3nj/mh3nj-themes/releases)
[![Stars](https://img.shields.io/github/stars/mh3nj/mh3nj-themes?color=yellow)](https://github.com/mh3nj/mh3nj-themes/stargazers)
[![Issues](https://img.shields.io/github/issues/mh3nj/mh3nj-themes?color=orange)](https://github.com/mh3nj/mh3nj-themes/issues)
[![Themes](https://img.shields.io/badge/themes-34-purple)](https://github.com/mh3nj/mh3nj-themes)
[![VS Code](https://img.shields.io/badge/vscode-%5E1.60.0-blueviolet)](https://code.visualstudio.com)

A family of 17 color themes for Visual Studio Code. Each theme comes in both light and dark variants, giving you 34 options to choose from. The colors are chosen to reduce eye strain during long coding sessions.

Created by mh3nj. Website: [mh3n.com](https://mh3n.com)

## Installation

This extension is not on the VS Code Marketplace. Install it manually from a release build.

### From a release VSIX

1. Go to the [Releases](https://github.com/mh3nj/mh3nj-themes/releases) page.
2. Download the latest `.vsix` file from the assets of that release.
3. Open Visual Studio Code.
4. Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X).
5. Click the `...` menu at the top of the Extensions panel.
6. Choose **Install from VSIX**.
7. Select the downloaded file.
8. Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P).
9. Run **Preferences: Color Theme** and pick a theme.

### From source

If you prefer to build it yourself, clone the repo and package it locally.

```bash
git clone https://github.com/mh3nj/mh3nj-themes.git
cd mh3nj-themes
npm install
npx @vscode/vsce package
```

This will generate a `.vsix` file in the project root. Install it using the same Install from VSIX step above.

### Updating

There is no auto update, since this is a GitHub only release. To update, download the newest `.vsix` from Releases, install it the same way, and VS Code will replace the old version.

## Theme Previews

| Theme | Light | Dark |
|-------|-------|------|
| Kahroba | ![Kahroba Light](screenshots/kahroba-light.png) | ![Kahroba Dark](screenshots/kahroba-dark.png) |
| Linen | ![Linen Light](screenshots/linen-light.png) | ![Linen Dark](screenshots/linen-dark.png) |
| Anar | ![Anar Light](screenshots/anar-light.png) | ![Anar Dark](screenshots/anar-dark.png) |
| Baran | ![Baran Light](screenshots/baran-light.png) | ![Baran Dark](screenshots/baran-dark.png) |
| Ember | ![Ember Light](screenshots/ember-light.png) | ![Ember Dark](screenshots/ember-dark.png) |
| Firouzeh | ![Firouzeh Light](screenshots/firouzeh-light.png) | ![Firouzeh Dark](screenshots/firouzeh-dark.png) |
| Harbor | ![Harbor Light](screenshots/harbor-light.png) | ![Harbor Dark](screenshots/harbor-dark.png) |
| Heather | ![Heather Light](screenshots/heather-light.png) | ![Heather Dark](screenshots/heather-dark.png) |
| Setareh | ![Setareh Light](screenshots/setareh-light.png) | ![Setareh Dark](screenshots/setareh-dark.png) |
| Simorgh | ![Simorgh Light](screenshots/simorgh-light.png) | ![Simorgh Dark](screenshots/simorgh-dark.png) |
| Zafaran | ![Zafaran Light](screenshots/zafaran-light.png) | ![Zafaran Dark](screenshots/zafaran-dark.png) |
| Zeytoon | ![Zeytoon Light](screenshots/zeytoon-light.png) | ![Zeytoon Dark](screenshots/zeytoon-dark.png) |
| Moss | ![Moss Light](screenshots/moss-light.png) | ![Moss Dark](screenshots/moss-dark.png) |
| Nilofar | ![Nilofar Light](screenshots/nilofar-light.png) | ![Nilofar Dark](screenshots/nilofar-dark.png) |
| Quartz | ![Quartz Light](screenshots/quartz-light.png) | ![Quartz Dark](screenshots/quartz-dark.png) |
| Sepehr | ![Sepehr Light](screenshots/sepehr-light.png) | ![Sepehr Dark](screenshots/sepehr-dark.png) |
| Yasi | ![Yasi Light](screenshots/yasi-light.png) | ![Yasi Dark](screenshots/yasi-dark.png) |

## Theme Details

### Kahroba
Warm amber and gold colors. The light version is soft and easy on the eyes. The dark version gives a cozy, warm feeling.

### Linen
Neutral beige and warm earth tones. It looks like natural linen fabric. Good for long coding sessions without distraction.

### Anar
Rich pomegranate reds and deep maroons. A bold choice if you like deep, warm colors.

### Baran
Cool blues and soft grays. Inspired by gentle rain. A calming palette that helps you focus.

### Ember
Warm oranges, reds, and browns. Like glowing embers. Energizing and passionate.

### Firouzeh
Turquoise and teal hues. Reminiscent of Persian turquoise. A refreshing and vibrant theme.

### Harbor
Deep blues and muted teals. Like a harbor at dusk. Calm and professional.

### Heather
Soft purples and mauves. Like heather fields in bloom. A gentle, floral palette.

### Setareh
Starry night inspired. Deep purples and blues with bright star accents. Dreamy and poetic.

### Simorgh
Mythical bird inspired. Rich purples, golds, and deep reds. A regal and majestic theme.

### Zafaran
Saffron inspired. Warm yellows, oranges, and deep reds. A spicy and energetic palette.

### Zeytoon
Olive greens and earthy tones. Inspired by olive groves. Natural and soothing.

### Moss
Deep greens and forest tones. Like moss on a forest floor. A rich, organic theme for nature lovers.

### Nilofar
Water lily inspired. Soft blues, greens, and pinks. A delicate and serene palette.

### Quartz
Cool grays and soft blues. Like quartz crystal. Clean, modern, and minimalist.

### Sepehr
Sky and space inspired. Deep blues, purples, and starry accents. Expansive and cosmic.

### Yasi
Jasmine inspired. Soft purples, pinks, and greens. A fragrant and gentle theme.

## Repository layout

```
mh3nj-themes/
├── screenshots/           preview images for every theme
├── kahroba-light.json     theme files, one per variant
├── kahroba-dark.json
├── ...
├── package.json           extension manifest
├── README.md
└── LICENSE
```

## Contributing

If you find a bug or have a suggestion, open an issue or submit a pull request. Contributions are welcome.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-idea`).
3. Commit your changes (`git commit -m 'Add your idea'`).
4. Push to the branch (`git push origin feature/your-idea`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Credits

Created by mh3nj.  
Website: [mh3n.com](https://mh3n.com)

If you enjoy these themes, please leave a star on the repo. It helps a lot :)
