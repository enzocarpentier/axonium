# 📝 Axonium Changelog

Follow Axonium's evolution through the solar system.

---

## v1.3.2 — Chopin
*January 11, 2026*

### New
- 🛡️ Brave's adblock-rust engine integration via UniFFI
- 💯 100% blocking score — 133/133 tests passed on adblock-tester
- 📋 +136k Safari rules — EasyList, EasyPrivacy, uBlock Filters, Peter Lowe's List + 62 custom rules
- 🎨 Cosmetic filtering — Hides residual ad elements (static and dynamic)
- 📐 New Blocker UI — Redesigned interface for lists, whitelist and blocking stats
- ⚡ Smart cache — Instant startup with Safari rules cache (versioning system)
- 📊 Per-site stats — Blocked elements counter per domain in Protection menu
- ✅ Quick whitelist — Add/remove site from whitelist in one click from tools menu
- 🔄 Auto-update — Filter lists refresh automatically every week
- 💬 Block notification — Small animated bubble when elements are blocked

### Improved
- Blocking engine optimized for Apple Silicon and Intel (Universal Binary)
- Blocker loads instantly thanks to smart cache
- Custom rules prioritized for optimal blocking
- Optimistic UI for whitelist (instant update)
- Non-blocking initialization — App starts immediately, blocking loads in background

### Fixed
- Handoff URL crash with invalid URLs (blob:, data:, about:)
- WebKit layers crash during rapid DOM deletions
- Leftover French UI elements (Mon espace, Copier, Imprimer)
- Address bar typing lag

---

## v1.3.1 — Debussy
*January 8, 2026*

### New
- 🆕 New logo and refreshed visual identity
- 📐 Sidebar toggle: show/hide the sidebar with one click

### Improved
- Smoother and more responsive sidebar animation
- General performance optimizations
- English set as default language

### Fixed
- Fixed French/English mix when language is set to English
- Fixed top bar overlapping content in fullscreen mode
- Popovers (tools, profile, etc.) no longer close the sidebar in auto mode
- Google Fonts no longer blocked by the ad blocker

---

## v1.3.0 — Vivaldi
*December 15, 2025*

### New
- ⌨️ Quick Open with ⌘K (Spotlight-like)
- 🔍 Smart filters @tabs, @history, @favorites
- 📁 Sessions: save and restore tab groups
- 🕐 Access to last 50 closed tabs

### Improved
- Autocomplete with intelligent scoring
- Smooth keyboard navigation in Quick Open
- Bilingual interface (FR/EN) for filters

---

## v1.2.5 — Tolstoj
*December 10, 2025*

### New
- 👤 Isolated user profiles (Work, Personal, Studies)
- 📖 Reader Mode with full customization
- 🔊 Text-to-Speech synthesis
- 📄 PDF export from Reader Mode
- 📸 Full page screenshot with annotations

### Improved
- Quick profile switch with ⌘⇧P
- Handoff & Continuity with iPhone/iPad

---

## v1.2.0 — Rachmaninoff
*December 1, 2025*

### New
- ☁️ Real-time iCloud sync
- 🔄 Selective sync: tabs, bookmarks, settings, passwords
- 🌍 Full French/English localization

### Improved
- Automatic system language detection
- Smart sync conflict resolution

---

## v1.1.0 — Borealis
*November 20, 2025*

### New
- ⭐ Bookmarks with unlimited hierarchical folders
- 🏷️ Colored tags to categorize bookmarks
- 📚 Thematic collections and reading lists
- 📥 Import/Export from Safari, Chrome, Firefox
- 🍪 Third-party cookie blocking via Content Blocker

### Improved
- Bookmarks sidebar with tree view
- Drag & Drop to reorganize

### Fixed
- Fixed white flash on page load

---

## v1.0.3 — Mercury
*November 15, 2025*

### New
- 🚀 Initial project release
- 🍎 100% native macOS browser in Swift/SwiftUI
- 🛡️ Native ad blocker (42+ rules)
- 📑 Vertical tabs with sidebar
- 🔐 Secure password manager (AES-256)

### Improved
- WebViews limit for performance (max 8)
- Do Not Track enabled by default
