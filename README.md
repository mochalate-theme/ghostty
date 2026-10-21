# mochalate - Ghostty

A dark theme for [Ghostty](https://ghostty.org), a cozy fusion of
[gruvbox](https://github.com/morhetz/gruvbox)'s warm earthiness and
[catppuccin](https://github.com/catppuccin/nvim)'s soft pastels, rendered in mochalate tones.

Warm brown-black backgrounds, burnt coral reds, amber yellows, sage greens and muted teals.

## Install

Use the install script (backs up existing themes):

```sh
./install.sh
```

Or copy the theme into Ghostty's themes directory:

```sh
cp themes/mochalate.conf ~/.config/ghostty/themes/mochalate
```

Then in `~/.config/ghostty/config`:

```conf
theme = mochalate
```

Or keep this repo cloned and point at it directly:

```conf
config-file = /path/to/mochalate/ghostty/themes/mochalate.conf
```

## Palette

| | Normal | | Bright |
| --- | --- | --- | --- |
| black | `#2c261e` | bright black | `#7a6850` |
| red | `#d06850` | bright red | `#d88078` |
| green | `#a8b878` | bright green | `#b0c888` |
| yellow | `#d8a050` | bright yellow | `#e8b870` |
| blue | `#88a0c0` | bright blue | `#a0b8d0` |
| magenta | `#e0a060` | bright magenta | `#c8a0d0` |
| cyan | `#78a890` | bright cyan | `#90c0a8` |
| white | `#e8d5c4` | bright white | `#f5ead8` |

Background `#1c1815`, foreground `#e8d5c4`, cursor `#e8d5c4` on `#1c1815`, selection
`#5c4030` with `#f5ead8` text.

## Credits

- [morhetz/gruvbox](https://github.com/morhetz/gruvbox): the warm, earthy foundation.
- [catppuccin/nvim](https://github.com/catppuccin/nvim): the soft pastel accent palette.

## License

[MIT](LICENSE)
