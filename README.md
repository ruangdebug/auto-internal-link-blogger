# Auto Internal Link for Blogger 🤖🔗

**Plugin JavaScript otomatis untuk membuat internal link di blog Blogger** — tanpa edit artikel satu per satu.

[![Version](https://img.shields.io/badge/version-3.0-blue.svg)](https://github.com/username/auto-internal-link-blogger)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Blogger](https://img.shields.io/badge/platform-Blogger-orange.svg)](https://blogger.com)

---

## ✨ Fitur

| Fitur | Deskripsi |
|-------|-----------|
| 🤖 **Otomatis** | Scan artikel lalu buat internal link tanpa edit manual |
| 🎯 **Relevan** | Algoritma scoring 45% threshold, hanya link yang relevan |
| ⚡ **Lazy Loading** | IntersectionObserver + requestIdleCallback, tidak membebani LCP |
| 💾 **Cache** | localStorage 1 jam, hemat bandwidth |
| 🔄 **Retry** | Exponential backoff jika feed Blogger error |
| 📊 **Analytics** | Tracking klik ke Google Analytics / GA4 otomatis |
| 🎨 **Customizable** | Atur via `data-*` attribute tanpa edit kode |
| 🛡️ **Smart Limits** | Max 2 link per paragraf, distribusi merata |
| 🔗 **Blacklist** | Tidak duplikat link yang sudah ada di artikel |

---

## 🚀 Cara Pakai

### 1. Copy kode ke Template Blogger

**Buka** Blogger → Tema → Edit HTML → Letakkan **sebelum** `&lt;/body&gt;`:

```html
<script src="https://cdn.jsdelivr.net/gh/ruangdebug/auto-internal-link-blogger@main/dist/auto-internal-link.js"></script>
