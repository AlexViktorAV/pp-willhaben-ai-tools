# Willhaben AI Tools

A robust, private browser extension built to enhance your browsing, appraisal, and listing experience on willhaben.at.

## Features
- **✨ AI Auto-Fill Form Integration:** Uses the modern `gemini-3.5-flash` engine (with a automatic seasonal fallback to `gemini-3.1-flash-lite`) to read uploaded image inputs and instantly complete target item headers, category trees, custom tags, and summaries.
- **📊 Live Price Appraisal Indexing:** Leverages client-side DOM parsing to silently scan live listings on the marketplace for current keywords, computing an outlier-resistant market spectrum (Cheapest vs Average vs Premium) based on organic data.
- **🖼️ Real-Time Scrollbox Feed:** Automatically populates an integrated 1:1 image layout horizontal slider displaying active matching market results with price tags directly beneath the upload panel.
- **🛠️ Layout Toolkit:** Toggle options for native Fullscreen structural expansion, forced Top-Ad hiding, corrupted thumbnail aspect ratio fixing, and mass-media ZIP archiving exporter.

## Installation
1. Download or clone this repository to your local machine.
2. Open Chrome/Edge and navigate to `chrome://extensions/`.
3. Enable **Developer mode** (top-right toggle).
4. Click **Load unpacked** and select the root directory containing these extension files.

## Privacy & Security
This extension values your privacy. All credentials, including your personal Google Gemini API Key, are saved strictly using local browser storage parameters (`chrome.storage.local`). No personal data, search habits, or user records are ever monitored, collected, or tracked by the developer.

## License
Distributed under the MIT License. See `LICENSE` for more information.
