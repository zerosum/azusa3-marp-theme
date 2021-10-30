# Azusa 3 theme for Marp

![GitHub release (latest by date)](https://img.shields.io/github/v/release/zerosum/azusa3-marp-theme)

Theme for [Marp](https://marp.app/) based on [Azusa 3](https://azusa3.sanographix.net/) template.

## Usage

### Marp for VS Code

`.vscode/settings.json` on your workspace
```json
{
  "markdown.marp.themes": [
    "https://github.com/zerosum/azusa3-marp-theme/releases/download/v{x.y.z}/azusa3.css"
  ]
}
```

`slides.md`
```markdown
---
marp: true
theme: azusa3
---

```

see also: [Use custom theme CSS - Marp for VS Code](https://github.com/marp-team/marp-vscode#use-custom-theme-css-%EF%B8%8F)
