# Claude — Zed Theme

A warm editor theme for [Zed](https://zed.dev) built on Anthropic's official Claude brand palette. Two variants: **Claude Light** and **Claude Dark**.

---

## Preview

### Claude Light

Off-white Pampas surfaces with dark warm text. Calm and readable in daylight.

### Claude Dark

Deep warm blacks with cream text and a terra cotta accent. Designed for long sessions in low light.

---

## Installation

Search for **Claude** in the Zed extension marketplace:

1. Open the command palette (`cmd+shift+p` / `ctrl+shift+p`)
2. Run **`zed: extensions`**
3. Search for `Claude` and install

Then set the theme in your settings:

```json
{
  "theme": {
    "mode": "system",
    "dark": "Claude Dark",
    "light": "Claude Light"
  }
}
```

---

## Palette

The theme is anchored to five official Claude brand colors:

| Name        | Hex                   | Role                               |
| ----------- | --------------------- | ---------------------------------- |
| Crail       | `#D97757` / `#C15F3C` | Primary accent, cursor, selections |
| Claude Dark | `#141413`             | Dark background                    |
| Pampas      | `#F4F3EE`             | Light background                   |
| Cloudy      | `#B0AEA5` / `#B1ADA1` | Muted text, icons, line numbers    |
| Claude Blue | `#6A9BCC`             | Types, links, git blame            |

---

## Syntax Highlighting

| Token               | Dark                    | Light                    |
| ------------------- | ----------------------- | ------------------------ |
| Keywords            | `#B07BA8` soft purple   | `#8050A0` purple         |
| Functions           | `#E8956A` warm orange   | `#C15F3C` Crail          |
| Strings             | `#7FB685` sage green    | `#3A8040` forest green   |
| Types               | `#6A9BCC` Claude blue   | `#3A70B0` blue           |
| Constants / numbers | `#D4A847` amber         | `#A07010` amber          |
| Comments            | `#514E47` muted, italic | `#B1ADA1` Cloudy, italic |
| Variables           | `#E8E6DC` base text     | `#1E1C19` base text      |
| Operators           | `#B0AEA5` Cloudy        | `#6E6A60` muted warm     |

---

## License

MIT
