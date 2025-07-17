  # OnlineFileExplorer

A modular, touch-friendly file explorer built in **vanilla JavaScript**.

> Use as `OnlineFileExplorer` or alias as `OFE`.

## ✨ Features

- Decreases carbon emmision footprint.
- Mobile-ready: long-press to select, double-tap to open
- Multi-selection via Ctrl/Shift (desktop) or long-press + tap (mobile)
- Bulk delete, drag-and-drop, breadcrumb navigation
- No dependencies beyond:
  - [vanilla-js-essentials](https://github.com/hazho/vanilla-JS-Essentials)
  - [vanilla-js-basics](https://github.com/hazho/vanilla-JS-Basics)

## 🧩 Usage

```js
import OFE from './dist/ofe.module.js';

const explorer = new OFE({
  fetchUrl: '/api/collections',
  csrfToken: '...'
});

explorer.delSlctd();
explorer.loadColl('abc123');
