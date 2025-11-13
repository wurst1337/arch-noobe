![logo](https://github.com/user-attachments/assets/f5c7eefc-a2ad-4166-a959-a94760a798c5)
# arch-noobe

Shell Bash script to make Arch Linux nice out of box experience.

## script description
Step by step:
- Searching best mirrors using `reflector`
- Updating system via `sudo pacman -Syuu`
- Installing best drivers for videocard (nvidia/amd/intel)
- Installing most used packages:
  - `firefox` or `chromium`
  - (optional) `steam`
  - (optional) `gamemode` and `lib32-gamemode`
  - (optional) `mangohud` and `lib32-mangohud`
  - `power-profiles-daemon`
- Enabling services using `systemctl`
- Installing `yay` or `paru` to get AUR access
- Removing unused packages (orphans) `pacman -Qdtq | pacman -Rns -`

## dependencies
- `Arch Linux`
- `coreutils`, including `bash`
- `pacman`
- `systemd`
- `git`

## license
Project uploaded under very permissive "MIT License" terms.
