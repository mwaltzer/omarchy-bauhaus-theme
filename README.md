# Omarchy Theme: Bauhaus

Updated for Omarchy 4, keeping the Omarchy 3 config files.

## Install

```bash
omarchy theme install https://github.com/mwaltzer/omarchy-bauhaus-theme
```

A Bauhaus-inspired dark theme with warm coral and sand accents over cool slate/teal surfaces.

<img width="3840" height="2560" alt="screenshot-2025-09-20_21-59-34" src="https://github.com/user-attachments/assets/f0b6952e-c436-4c03-b496-0ecc6679210a" />

## Palette
- Primary Background:   #101318 (deep slate-black)
- Secondary Background: #161B22 (soft charcoal)
- Tertiary Background:  #222733 (lifted cool surface)
- Primary Accent:       #E37B66 (coral)
- Secondary Accent:     #E0A568 (sand)
- Tertiary Accent:      #809D9E (muted teal)
- Text Primary:         #EAEFF5 (near-porcelain)
- Text Secondary:       #C6CED8 (cool mist)
- Text Dim:             #98A0AE (slate gray-blue)
- Success:              #789FA2
- Warning:              #E7A46F
- Error:                #CB886D
- Info:                 #8999AA
- Selection Background: #2B3040

## colors.toml
Omarchy 4 generates every app config (terminals, btop, Hyprland borders, the shell bar, editors) from `colors.toml`, which mirrors `palette.yml`. The per-app files below are used by Omarchy 3.

## palette.yml
Includes machine-readable values for:
- Core surfaces: primary_bg, secondary_bg, tertiary_bg, selection_bg
- Text ramp: text_primary, text_secondary, text_dim
- Accents: primary_accent, secondary_accent, tertiary_accent, success, warning, error, info
- Terminal palettes: ansi_normal, ansi_bright, ansi_dim

## Integrations
- eza.yml (list colors for eza)
- ghostty.conf (terminal palette)
- kitty.conf (terminal palette)
- swayosd.css (OSD styling)
- vscode.json (placeholder reference)

