[prettier-badge]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square
[prettier-link]: https://github.com/prettier/prettier
[release-badge]: https://img.shields.io/github/v/release/ClearVision/ClearVision-v7?include_prereleases&style=flat-square
[release-link]: https://github.com/ClearVision/ClearVision-v7/releases
[license-badge]: https://img.shields.io/github/license/ClearVision/ClearVision-v7?style=flat-square
[license-link]: https://github.com/ClearVision/ClearVision-v7/blob/master/LICENSE
[discord-badge]: https://discord.com/api/guilds/212324635356692500/widget.png?style=shield
[discord-link]: https://clearvision.github.io/join
[issues-badge]: https://img.shields.io/github/issues/ClearVision/ClearVision-v7?style=flat-square
[issues-link]: https://github.com/ClearVision/ClearVision-v7/issues
[prs-badge]: https://img.shields.io/github/issues-pr/ClearVision/ClearVision-v7?style=flat-square
[prs-link]: https://github.com/ClearVision/ClearVision-v7/pulls
[sass-badge]: https://img.shields.io/badge/Sass-CC6699.svg?style=flat-square&logo=sass&logoColor=white
[sass-link]: https://sass-lang.com/

<div align="center">

# ClearVision v7

[![code style: prettier][prettier-badge]][prettier-link]
[![Language: Sass][sass-badge]][sass-link]
[![License][license-badge]][license-link]
[![Discord Server][discord-badge]][discord-link]
[![Issues][issues-badge]][issues-link]
[![Pull Requests][prs-badge]][prs-link]

<img  width="500" src="https://raw.githubusercontent.com/ClearVision/ClearVision-v7/refs/heads/master/screenshots/treatment-2.jpg">
<img  width="500" src="https://raw.githubusercontent.com/ClearVision/ClearVision-v7/refs/heads/master/screenshots/treatment-3.jpg">

</div>

### Presets
List of presets available. All primarily for dark mode
- Sapphire - Darkish blue | Art: https://www.deviantart.com/kuldarleement/art/Stellar-collision-397866757 ; https://www.deviantart.com/kuldarleement/ ; http://www.kuldarleement.eu/  
- Ruby - Red | Art: https://www.deviantart.com/artistmef/art/Follow-the-path-279366207 ; https://www.deviantart.com/artistmef/  
- Amber - Orange | Art: https://www.deviantart.com/chromamancer/art/War-March-201045286 ; https://www.furaffinity.net/view/5408230 ; https://www.furaffinity.net/user/chromamancer/  
- Emerald - Green | Art: Work from "Guild Wars" or "Guild Wars 2" ; http://www.kekaiart.com/guild-wars-2.html ; http://www.kekaiart.com/uploads/5/4/7/6/5476798/7976137_orig.jpg ; http://www.kekaiart.com/t  
- Amethyst - Magenta | Art (tinted purple): https://www.deviantart.com/vityar83/art/gulls-149920115 ; https://www.deviantart.com/vityar83  
- Halloween - Orange, for festivity | Art: https://www.deviantart.com/unidcolor/art/Halloween-2014-491224711 ; https://www.deviantart.com/unidcolor/  
- Winter - Light blue, for festivity | Art: https://wall.alphacoders.com/big.php?i=114938 ; unknown artist.

Goals:
- Supports visual refresh - New UI with new chat input & new UI with old chat input
- Supports both light and dark, along with dark variants
- Supports saturation setting
- Uses smallest css target possible
- Plugin support in extra files for respective client mods

## Theme Editor

Currently not available

## Installing

Note: ClearVision doesn't actively support plugins (as in, we don't seek out and actively theme fixes to every new plugin). However, when a plugin is widely used, we try our best to stay compatible.

**For BD and Vencord:**

Download the theme file from [our official support server](https://clearvision.github.io/join), [the BetterDiscord Website](https://betterdiscord.app/theme/ClearVision) or [releases](https://github.com/ClearVision/ClearVision-v6/releases) and move it into your injector's themes folder:

- BetterDiscord: `%appdata%\betterdiscord\themes`
- Vencord: `%appdata%\vencord\themes`

**For using the theme online:**

There are multiple ways to do this if your client offers using an online version. The suggested two are `https://clearvision.github.io/ClearVision-v7/main.css` or `https://raw.githubusercontent.com/ClearVision/ClearVision-v7/master/ClearVision-v7.theme.css`

For customizing the theme from there, you'll want to use custom css and add any variables you'd like to change. It should look something like this:

```
:root {
	--main-color: red;
	--hover-color: yellow;
}
```

## Building from source

To build the theme from source, first install npm from the dependencies below, then you can run `pnpm install` to install all missing dependencies and `pnpm run build` to compile the theme into the `/public` folder.

### Dependencies

- [NodeJS/npm](https://nodejs.org/)
- [pnpm](https://www.npmjs.com/package/pnpm)
- [sass](https://www.npmjs.com/package/sass)
- [PostCSS Autoprefixer](https://www.npmjs.com/package/autoprefixer)
- [PostCSS CLI](https://www.npmjs.com/package/postcss-cli)

## Contributing

Run `pnpm run test` to compile the theme.

The `main.css` file builds to the `/test` directory, which can then be copied into your client mod's Custom CSS or placed in the themes folder and enabled in settings. Just make sure any other themes are disabled for testing.

## Support
Join our [discord server](https://discord.gg/dHaSxn3) and post in our support channel if you need additional help!
