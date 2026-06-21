
# vifm-catppuccin

[Catppuccin](https://catppuccin.com) colour schemes for [vifm](https://vifm.info),
covering all four flavours: **Latte**, **Frappé**, **Macchiato**, and **Mocha**.


## Install

Make sure the colours directory exists, then grab the flavours single flavour:

```sh
mkdir -p ~/.config/vifm/colors
wget -P ~/.config/vifm/colors \
  https://raw.githubusercontent.com/justdanyul/vifm-catppuccin/main/vifm-colors/catppuccin-mocha.vifm
```

## Usage

Try a scheme live from inside vifm:

```
:colorscheme catppuccin-mocha
```

To make it permanent, add the line to your `~/.config/vifm/vifmrc`:

```
colorscheme catppuccin-mocha
```

Of course, swapping `catppuccin-mocha` for `catppuccin-latte`, `catppuccin-frappe`, or
`catppuccin-macchiato` based on preference.

> [!NOTE]
> For the exact palette, your terminal needs true-colour support
> (`echo $COLORTERM` should report `truecolor` or `24bit`). 

