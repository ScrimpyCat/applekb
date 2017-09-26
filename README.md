# applekb
XKB layout for supporting Apple Magic Keyboard and using the left Command key for CTRL

Swaps the left command key with the control key. While keeping the right command key mapped to super.

## Installation

Place folders in your `~/.xkb` directory.

```
.xkb/
├── keymap
│   └── applekbd
└── symbols
    └── appleswap
```

Run with: `xkbcomp -I$HOME/.xkb ~/.xkb/keymap/applekbd $DISPLAY`
