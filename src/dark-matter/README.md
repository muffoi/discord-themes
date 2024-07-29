# Dark Matter
A remake of an [eponymous BetterDiscord theme](https://betterdiscord.app/theme/Dark%20Matter).

This remake includes various fixes, such as:
- Not working **transparency**
- Discord's custom Windows **window title bar** lacking color
- **Rounded borders** that look bad with transparent themes
- Too big **scrollbars**
- **Unaligned items** in server list

**Note: The *Visual Refresh* experiment is not fully supported by this theme yet. No compatibility is guaranteed.**

## Usage
To use with Vencord, paste the following link in the online themes textbox:
`https://muffoi.github.io/discord-themes/src/dark-matter/DarkMatter.theme.css`

## Customization

This theme allows changes to transparency of various elements, using *QuickCSS* and `:root` variables:

- `--opacity-chat`: Controls transparency of (voice) chats (`0.8`*)
- `--opacity-1`: Member list and user profile sidebar (`0.5`)
- `--opacity-2`: Server list and top bar in channels (`1`)
- `--opacity-3`: DM/channels list, settings sidebar (`0.9`)
- `--opacity-frame`: Window title bar on Windows (`1`)

**Default value*