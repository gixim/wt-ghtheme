# wt-ghtheme

This is a GitHub-like theme for Windows Terminal.

I used [Color - Primer](https://primer.style/brand/primitives/color/) found on [Color - Brand Toolkit](https://brand.github.com/foundations/color) to create this theme.

## Installation

1. Copy the contents of schemes/ghdark.json into your `scheme` section in settings.json of Windows Terminal
2. Change `colorScheme` on `profiles` section to "GitHub Dark"

```jsonc
// settings.json of Windows Terminal
{
    "profiles": 
    {
        "defaults": 
        {
            "colorScheme": "GitHub Dark",
        },
    },
    "schemes": 
    [
        {
            "name": "GitHub Dark",
            "background": "#0D1117",
            "foreground": "#F0F6FC",
            // ...
        }
    ],
    "themes": []
}
```

## Uninstallation

Delete the contents what you've write in the "Installation" section.
