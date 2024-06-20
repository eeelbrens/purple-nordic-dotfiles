# Purple Nordic Dotfiles (a personal dotfile for use on Sway WM)
This is my first time using (and actually setting down to rice) a window manager (coming from GNOME), and I'm probably never coming back!
And so these are my personal dotfiles for anyone to try and apply. Enjoy!
I wrote this theme from scratch, tho some kudos goes to [this rice](https://github.com/rubyowo/dotfiles) for inspiration.
> [!NOTE]
> I'm a bit frequent in my updates to these dotfiles as I add extra functionality to my setup (as long as I'm not changing any one pixel of my screenshoted look). Don't take that with a deal-breaking stance, you could always commit those changes to your setup as well!

## Previews
![2024-06-20T01:42:43,631663306+03:00](https://github.com/eeelbrens/purple-nordic-dotfiles/assets/130598002/3eeaaab1-d388-4d5e-94c5-399e4064a5d3)
![2024-06-20T01:42:46,506635907+03:00](https://github.com/eeelbrens/purple-nordic-dotfiles/assets/130598002/7ab5b5c2-8442-4eb3-81cb-428376333e89)
![2024-06-20T01:56:30,321352929+03:00](https://github.com/eeelbrens/purple-nordic-dotfiles/assets/130598002/6f0fa8e5-1e2b-4fab-a819-1f1360b89764)

## Packages/Dependencies Used
### swaywm and co. (major UI elements)
- wm: [`sway`](https://github.com/swaywm/sway) (the base of this whole rice obv)    
> [!NOTE]
> The config files for sway depend on gnome (as in `$gnome-schema`) for global font, GTK, and icon theming, as well as for user authentication within `nautilus` (via `polkit`). You may want to remove/rewrite those portions accordingly).
- main bottom bar: [`waybar`](https://github.com/Alexays/Waybar)
- lockscreen: [`swaylock`](https://github.com/swaywm/swaylock) (not shown)
- notification daemon: [`dunst`](https://github.com/dunst-project/dunst)
- app launcher: [`wofi`](https://sr.ht/~scoopta/wofi/)
- progress bar: [`wob`](https://github.com/francma/wob) (not shown)

### extra dependencies required (check after your sway installation!)
- sway: `brightnessctl` `playerctl` `pamixer` `wob` (audio/brightness keybindings), `polkit`/`polkit-gnome-authentication` (user authentication for `nautilus`), `grimshot` (for screenshots), `swayidle` (for idle settings)
- waybar: `playerctl` (for MPRIS media module)

### terminal stuff
- terminal: [`kitty`](https://github.com/kovidgoyal/kitty)
- text editor: [`nvim`](https://github.com/neovim/neovim) with [LazyVim](https://github.com/LazyVim/LazyVim) (config files for LazyVim are **NOT** included in this repo)
- fetch: [`fastfetch`](https://github.com/fastfetch-cli/fastfetch) (with custom colored logo options)
- color animation: [`pipes.sh`](https://github.com/pipeseroni/pipes.sh)

### theming stuff
- theme: [`catppuccin`](https://github.com/catppuccin/catppuccin) frappe
- firefox theming: [`cascade`](https://github.com/cascadefox/cascade) and [Adaptive Tab Bar Colour](https://github.com/easonwong-de/Adaptive-Tab-Bar-Colour) extension
> [!NOTE]
> The chrome folder contains my own firefox configs file for cascade. Only the cascade-colours.css file is commented out and had its color theme management to Adaptive Tab Bar Colour.
- theme for websites: [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
- fonts: [Jetbrains Mono](https://github.com/JetBrains/JetBrainsMono) (monospace, OG non-nerd variant), [Rubik](https://fonts.google.com/specimen/Rubik) (sans-serif)
- cursor: [Bibata-Modern-Classic](https://www.bibata.live/) (not shown in screenshots)
