# Project README Template — npm Package / Library

For open-source libraries, SDKs, and CLI tools. Uses coolreadme.xyz editorial cards.
No signup, no config — replace params and paste.

## Copy This

```markdown
<div align="center">

[![my-package](https://coolreadme.xyz/api/docs-card?pkg=my-package&version=1.0.0&desc=A+one-line+description+of+what+this+does&install=npm+install+my-package&theme=langchain)](https://npmjs.com/package/my-package)

[![npm](https://coolreadme.xyz/api/npm-card?pkg=my-package)](https://npmjs.com/package/my-package)

</div>

---

## Install

```bash
npm install my-package
```

## Usage

```typescript
import { something } from 'my-package'

something({ option: true })
```

---

## Latest Post

[![Article](https://coolreadme.xyz/api/article-card?title=Why+I+built+my-package&excerpt=A+short+description+of+the+article+or+changelog+entry&tag=Release&author=YOURNAME&theme=dark)](https://your-blog-post-url)

---

## Built by

[![Profile](https://coolreadme.xyz/api/hacker?user=YOURNAME&status=SHIPPING+CODE&accent=00FF88)](https://github.com/YOURNAME)

---

<div align="center">

[![MIT License](https://img.shields.io/badge/License-MIT-00FF88?style=for-the-badge)](LICENSE)
[![npm version](https://img.shields.io/npm/v/my-package?style=for-the-badge&color=CB3837)](https://npmjs.com/package/my-package)

</div>
```

## Card Params Reference

### `/api/docs-card` — SDK / package install card

| Param | Description | Example |
|-------|-------------|---------|
| `pkg` | Package name | `teleping` |
| `version` | Version string | `1.0.0` |
| `desc` | Short description | `Telegram alerts for solo builders` |
| `install` | Install command | `npm install teleping` |
| `theme` | `langchain` (navy/cyan) · `dark` · `minimal` | `langchain` |

```markdown
[![docs](https://coolreadme.xyz/api/docs-card?pkg=PKG&version=VERSION&desc=DESC&install=INSTALL_CMD&theme=langchain)](https://npmjs.com/package/PKG)
```

### `/api/npm-card` — live npm stats

| Param | Description |
|-------|-------------|
| `pkg` | Package name (fetches live version + weekly downloads) |

```markdown
[![npm](https://coolreadme.xyz/api/npm-card?pkg=PKG)](https://npmjs.com/package/PKG)
```

### `/api/article-card` — blog post / changelog entry

| Param | Description | Example |
|-------|-------------|---------|
| `title` | Post title | `Why I built this` |
| `excerpt` | Short excerpt | `The story behind the library` |
| `tag` | Category pill | `Release` · `Tutorial` · `Deep Dive` |
| `author` | GitHub username | `yourname` |
| `theme` | `medium` (light) · `dark` | `dark` |
| `img` | Optional thumbnail URL | — |

```markdown
[![article](https://coolreadme.xyz/api/article-card?title=TITLE&excerpt=EXCERPT&tag=TAG&author=YOURNAME&theme=dark)](https://your-post-url)
```

## Real-World Example — teleping

> [`teleping`](https://github.com/yerdaulet-damir/teleping) — Telegram alerts for solo builders.

```markdown
[![teleping](https://coolreadme.xyz/api/docs-card?pkg=teleping&version=0.2.1&desc=Telegram+alerts+for+vibe+coders.+Know+what+broke+and+what+shipped+%E2%80%94+the+moment+it+happens.&install=npm+install+teleping&theme=langchain)](https://npmjs.com/package/teleping)

[![npm](https://coolreadme.xyz/api/npm-card?pkg=teleping)](https://npmjs.com/package/teleping)
```

## Best For

- npm packages, SDKs, CLI tools
- Libraries with a changelog or blog
- Solo devs who want a slick project page without design work
- Any project that installs via `npm install`
