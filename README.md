# 📱 WhatsApp Number Sanitizer & Formatter

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A lightweight, high-performance, single-page application (SPA) designed to clean, sanitize, and format messy lists of phone numbers into standardized international WhatsApp formats instantly.

![WhatsApp Number Sanitizer Banner]([https://github.com/thorifzhafran/wa-fixer/blob/main/Screenshot%202026-09-27%20225155.png](https://github.com/thorifzhafran/wa-fixer/blob/main/Screenshot%202026-09-27%20225155.png?raw=true)) <!-- Replace with real screenshot if available -->

---

## ✨ Features

- ⚡ **Instant Processing**: Converts raw text into sanitized numbers in real-time as you type or paste.
- 🌍 **International Prefix Customization**: Supports multiple country presets (Indonesia `+62`, USA `+1`, UK `+44`, India `+91`, etc.) and custom numeric prefixes.
- 🧹 **Automatic Deduplication**: Option to automatically filter out duplicate numbers in your list.
- ➕ **Flexible Styling**: Toggle leading `+` prefix formatting (e.g., `+62812...` vs `62812...`).
- 📁 **Export Utilities**: One-click **Copy to Clipboard** or export directly to **.TXT** and **.CSV** files.
- 🔒 **100% Client-Side Privacy**: All processing runs locally in your browser. No data or phone numbers are ever sent to external servers.
- 🎨 **Modern WhatsApp UI**: Built with a clean, clean WhatsApp-inspired green palette and fully responsive across mobile, tablet, and desktop devices.
- 🔍 **SEO & Schema Ready**: Embedded with structured JSON-LD Schema markup for web performance and search engines.

---

## 🛠️ Built With

* **Markup & Logic**: HTML5, Vanilla JavaScript (ES6+)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) (CDN)
* **Icons**: [Feather Icons](https://feathericons.com/)
* **UI Modals & Toasts**: [SweetAlert2](https://sweetalert2.github.io/)

---

## 🚀 Getting Started

Since this project is built as a single-file SPA, setup is extremely simple.

### Prerequisites
All dependencies are loaded via fast CDN links. You only need a modern web browser (Chrome, Firefox, Safari, Edge).

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/whatsapp-number-sanitizer.git
   ```
2. Navigate to the project folder:
   ```bash
   cd whatsapp-number-sanitizer
   ```
3. Open `index.html` in your web browser.

---

## 📖 How It Works

1. **Paste Raw Numbers**: Paste any unformatted list into the **Raw Data Input** area (supports dashes, spaces, parentheses, and leading zeros).
2. **Configure Settings**: Select your desired target **Country Code**, choose whether to include the `+` prefix, or toggle deduplication.
3. **Copy or Download**: Use the **Copy Result** button or export your clean list as a `.TXT` or `.CSV` file.

### Input / Output Example

| Raw Input (Before) | Cleaned Output (After) |
| :--- | :--- |
| `0896 9530 9913` | `6289695309913` |
| `+62 812-3445-3444` | `6281234453444` |
| `0812(3456)7890` | `6281234567890` |

---

## 👤 Author & Credits

Created with ❤️ by **[Thorif Zhafran](https://thorifzhafran.com)** in partnership with **[Webinesia](https://webinesia.com)**.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
