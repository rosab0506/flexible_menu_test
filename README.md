# 🏦 Настройки банков

> A polished, single-file bank management UI built with pure HTML & CSS — no frameworks, no dependencies.

---

## ✨ Features

- **Filter bar** — status dropdown with checkboxes, date range picker, and a smart reset button that only appears when filters are active
- **Bank table** — sortable rows with drag handles, logo thumbnails, mortgage program info, iOS-style status toggles, and inline edit/delete actions
- **Edit modal** — large, screen-proportional modal with tabbed content (main info + mortgage programs), logo upload, manager comments, and a save action that triggers a toast
- **Skeleton loading** — shimmer animation on table rows while data "loads"
- **Toast notifications** — slide-in confirmation on save or toggle change
- **Fully Russian UI** — all labels, placeholders, and copy in Russian

---

## 🚀 Getting Started

No build step. No install. Just open the file.

```bash
# Clone or download, then:
open index.html
```

Or drag `index.html` into any browser.

---

## 🗂 Structure

```
index.html        # Everything — styles, markup, and scripts in one file
README.md         # You are here
```

---

## 🖼 UI Overview

| Section | Description |
|---|---|
| Toggle row | Global switches for акционная стоимость, лимиты ипотеки, МСК/СПБ |
| Filter bar | Status multi-select dropdown + creation date range |
| Bank table | Checkbox, drag handle, logo, programs, toggle, actions |
| Edit modal | Two-tab form with logo upload, bank name, comments, active toggle |
| Toast | Auto-dismissing success notification |

---

## 🎨 Design Tokens

| Token | Value |
|---|---|
| Primary blue | `#4f7ef8` |
| Danger red | `#e53935` |
| Success green | `#34c759` |
| Background | `#f5f6fa` |
| Card surface | `#ffffff` |
| Border | `#dde1e7` |
| Text primary | `#1a1a2e` |
| Text muted | `#aaa` |

---

## 🛠 Tech

- **HTML5** — semantic markup
- **CSS3** — custom properties, flexbox, CSS animations, `backdrop-filter`, `mask-image`
- **Vanilla JS** — dropdown logic, modal, tab switching, skeleton loader, toast

---

## 📋 Requirements Covered

- [x] Flexible filter menu with calendar date pickers and dropdowns
- [x] Red apply / reset button behavior
- [x] CSS pseudo-element icon with hover effects
- [x] Modal with blurred backdrop, conditional tab content, close on overlay click
- [x] Edit modal opens on row edit button click
- [x] All text in Russian
- [x] Reset button hidden by default, visible only when filters are active
- [x] Loading skeleton state on table

---

<p align="center">Built as a frontend test task · Pure HTML/CSS/JS</p>
